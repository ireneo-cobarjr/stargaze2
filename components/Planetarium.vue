<template>
    <div class="planetarium">
        <svg viewBox="0 0 100 100" xmlns="http://www.w3.org/2000/svg">
            <circle class="planets mercury" cx="3" cy="30" r="8%" fill="#e53935" stroke="#e53935" stroke-width=".25"/>
            <circle class="planets venus" cx="80" cy="70" r="9%" fill="#ffeb3b" stroke="#ffeb3b" stroke-width=".4"/>
            <circle class="planets earth" cx="100" cy="40" r="10%" fill="#4caf50" stroke="#4caf50" stroke-width=".3"/>
            <circle class="planets mars" cx="90" cy="90" r="5%" fill="#d50000" stroke="#d50000" stroke-width=".13"/>
            <circle class="planets jupiter" cx="2" cy="90" r="20%" fill="#795548" stroke="#795548" stroke-width=".8"/>
            <circle class="planets saturn" cx="63" cy="15" r="18%" fill="#9c27b0" stroke="#9c27b0" stroke-width=".56"/>
            <circle class="planets neptune" cx="28" cy="18" r="15%" fill="#4fc3f7" stroke="#4fc3f7" stroke-width=".36"/>
            <circle class="planets uranus" cx="50" cy="80" r="10%" fill="#2196f3" stroke="#2196f3" stroke-width=".42"/>
            <circle class="planets pluto" cx="2" cy="60" r="5%" fill="#212121" stroke="#212121" stroke-width=".1"/>
        </svg>
    </div>
</template>
<script>
export default {
    
}
</script>

<style lang="scss" scoped>
.planetarium {
    height: 70vh;
    width: 100vw;

    svg {
        height: 70vh;
        width: 100vw;

        .planets {
            opacity: 0.1;
        }
    }
}

.mercury {
    animation-name: mercury;
    animation-iteration-count: infinite;
    animation-timing-function: linear;
    animation-duration: 28s;
}
@keyframes mercury {
    0% { stroke-width: .25; cx: 3; cy: 30;}
    10% { stroke-width: 12; cx: 5; cy: 35;}
    20% { stroke-width: 42; cx: 7; cy: 40;}
    50% { stroke-width: 89; cx: 10; cy: 42;}
    80% { stroke-width: 42; cx: 7; cy: 40;}
    90% { stroke-width: 12; cx: 5; cy: 35;}
    100% { stroke-width: .25; cx: 3; cy: 30;}
} 

.venus {
    animation-name: venus;
    animation-iteration-count: infinite;
    animation-timing-function: linear;
    animation-duration: 120s;
}
@keyframes venus {
    0% { stroke-width: .4;}
    30% { stroke-width: 87;}
    45% { stroke-width: 158;}
    50% { stroke-width: 269;}
    55% { stroke-width: 158;}
    70% { stroke-width: 87;}
    100% { stroke-width: .4;}
} 

.earth {
    animation-name: earth;
    animation-iteration-count: infinite;
    animation-timing-function: linear;
    animation-duration: 20s;
}
@keyframes earth {
    0% { stroke-width: .3;}
    20% { stroke-width: 5;}
    35% { stroke-width: 12;}
    50% { stroke-width: 36;}
    65% { stroke-width: 12;}
    80% { stroke-width: 5;}
    100% { stroke-width: .3;}
} 

.mars {
    animation-name: mars;
    animation-iteration-count: infinite;
    animation-timing-function: linear;
    animation-duration: 80s;
}
@keyframes mars {
    0% { stroke-width: .13;}
    20% { stroke-width: 52;}
    35% { stroke-width: 85;}
    50% { stroke-width: 120;}
    65% { stroke-width: 85;}
    80% { stroke-width: 52;}
    100% { stroke-width: .13;}
} 

.jupiter {
    animation-name: jupiter;
    animation-iteration-count: infinite;
    animation-timing-function: linear;
    animation-duration: 180s;
}
@keyframes jupiter {
    0% { stroke-width: .13;}
    20% { stroke-width: 252;}
    35% { stroke-width: 320;}
    50% { stroke-width: 400;}
    65% { stroke-width: 320;}
    80% { stroke-width: 252;}
    100% { stroke-width: .13;}
} 


.saturn {
    animation-name: saturn;
    animation-iteration-count: infinite;
    animation-timing-function: linear;
    animation-duration: 800s;
}
@keyframes saturn {
    0% { stroke-width: .56;}
    20% { stroke-width: 154;}
    35% { stroke-width: 595;}
    50% { stroke-width: 700;}
    65% { stroke-width: 595;}
    80% { stroke-width: 154;}
    100% { stroke-width: .56;}
} 

.neptune {
    animation-name: neptune;
    animation-iteration-count: infinite;
    animation-timing-function: linear;
    animation-duration: 210s;
}
@keyframes neptune {
    0% { stroke-width: .36;}
    20% { stroke-width: 12;}
    35% { stroke-width: 85;}
    50% { stroke-width: 500;}
    65% { stroke-width: 85;}
    80% { stroke-width: 12;}
    100% { stroke-width: .36;}
} 

.uranus {
    animation-name: uranus;
    animation-iteration-count: infinite;
    animation-timing-function: linear;
    animation-duration: 400s;
}
@keyframes uranus {
    0% { stroke-width: .42;}
    20% { stroke-width: 120;}
    35% { stroke-width: 550;}
    50% { stroke-width: 560;}
    65% { stroke-width: 550;}
    80% { stroke-width: 120;}
    100% { stroke-width: .42;}
} 

.pluto {
    animation-name: pluto;
    animation-iteration-count: infinite;
    animation-timing-function: linear;
    animation-duration: 700s;
}
@keyframes pluto {
    0% { stroke-width: .1;}
    20% { stroke-width: 59;}
    35% { stroke-width: 320;}
    50% { stroke-width: 490;}
    65% { stroke-width: 320;}
    80% { stroke-width: 59;}
    100% { stroke-width: .1;}
} 
</style>

