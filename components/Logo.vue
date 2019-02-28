<template>
<svg :width="size" :height="size" viewBox="0 0 900 900" fill="none" xmlns="http://www.w3.org/2000/svg">
    <g clip-path="url(#clip0)">
        <rect x="-4" y="449.28" width="640" height="640" rx="30" transform="rotate(-44.8663 -4 449.28)" fill="#C4C4C4"/>
        <rect x="3.07105" y="449.297" width="630" height="630" rx="25" transform="rotate(-44.8663 3.07105 449.297)" fill="#96B6C1" stroke="#96B6C1" stroke-width="10"/>
        <path d="M305.139 426.571L515.892 68.9848L663.358 216.895L305.139 426.571Z" fill="#0D0D0D"/>
        <path d="M587.939 468.246L377.815 826.205L230.089 678.555L587.939 468.246Z" fill="#0D0D0D"/>
    </g>
    <defs>
        <clipPath id="clip0">
            <rect width="900" height="900" fill="white"/>
        </clipPath>
    </defs>
</svg>
</template>
<script>
export default {
    props: {
        size: {
            type: Number,
            default: 128
        }
    }
}
</script>

