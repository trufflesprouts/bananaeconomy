<script>
    import { onMount } from "svelte";
    const props = $props();
    let offset = $state(0);
    let animationFrame = 0;
    onMount(() => {
        const animate = () => {
            offset = (offset + 1) % 3000;
            animationFrame = requestAnimationFrame(animate);
        };
        animationFrame = requestAnimationFrame(animate);
        return () => {
            cancelAnimationFrame(animationFrame);
        };
    });
    const text = props.text.repeat(30);
</script>

<svg
    viewBox="0 0 2200 5710"
    preserveAspectRatio="xMidYMid meet"
    xmlns="http://www.w3.org/2000/svg"
>
    <defs>
        <path
            id="curvePath"
            d="M0.5 0C0.5 127.991 125.261 610.726 474.001 654.061C1042.86 724.748 1267.53 654.061 1572.55 824.572C2080.57 1108.57 2188.13 2438.21 2038.15 5710"
        />
    </defs>
    <text fill="currentColor">
        <textPath href="#curvePath" startOffset="{-offset}px">
            {text}
        </textPath>
    </text>
</svg>

<style>
    svg {
        position: absolute;
        z-index: -1;
        width: 110vw;
        height: auto;
        top: 160px;
        left: 20px;
        transform: rotate(-5deg);
        pointer-events: none;
    }
    text {
        font-size: 100px;
        color: #c88f1a;
        letter-spacing: 26px;
    }
    @media (min-width: 450px) {
        svg {
            top: 100px;
        }
    }
    @media (min-width: 550px) {
        svg {
            top: 50px;
        }
    }
    @media (min-width: 800px) {
        svg {
            transform: none;
            top: 0;
            right: 0;
            left: unset;
            width: 65vw;
        }
    }
    @media (min-width: 1300px) {
        svg {
            right: 30px;
            width: 50vw;
            height: auto;
        }
    }
</style>
