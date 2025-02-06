# Hierarquia de tamanho de fonte

<style>
    .element {
        display: flex;
        align-items: center;
        gap: 3rem;

        height: 7.2rem;
    }

    .element:hover {
        cursor: pointer;
    }

    .tag,
    .size,
    .text {
        display: inline-block;
    }

    .tag,
    .size {
        font-size: 1.333rem;

        text-align: center;

        width: 6rem;
    }

    .element--1 .text {
        font-size: 4.778rem;
    }
    .element--2 .text {
        font-size: 3.981rem;
    }
    .element--3 .text {
        font-size: 3.318rem;
    }
    .element--4 .text {
        font-size: 2.765rem;
    }
    .element--5 .text {
        font-size: 2.304rem;
    }
    .element--6 .text {
        font-size: 1.920rem;
    }
    .element--7 .text {
        font-size: 1.6rem;
    }
    .element--8 .text {
        font-size: 1.333rem;
    }
    .element--9 .text {
        font-size: 1.111rem
    }
</style>

Assumindo que o tamanho da fonte do corpo corresponde a 10px, temos que a hierarquia de tamanhos de fonte é como segue:

<div>
    <div class="element element--1">
        <div class="tag">h1</div>
        <div class="size">4.778rem</div>
        <div class="text">The quick fox jumps</div>
    </div>
    <div class="element element--2">
        <div class="tag">h2</div>
        <div class="size">3.981rem</div>
        <div class="text">The quick fox jumps</div>
    </div>
    <div class="element element--3">
        <div class="tag">h3</div>
        <div class="size">3.318rem</div>
        <div class="text">The quick fox jumps</div>
    </div>
    <div class="element element--4">
        <div class="tag">h4</div>
        <div class="size">2.765rem</div>
        <div class="text">The quick fox jumps</div>
    </div>
    <div class="element element--5">
        <div class="tag">h5</div>
        <div class="size">2.304rem</div>
        <div class="text">The quick fox jumps</div>
    </div>
    <div class="element element--6">
        <div class="tag">h6</div>
        <div class="size">1.920rem</div>
        <div class="text">The quick fox jumps</div>
    </div>
    <div class="element element--7">
        <div class="tag">p</div>
        <div class="size">1.600rem</div>
        <div class="text">The quick fox jumps</div>
    </div>
    <div class="element element--8">
        <div class="tag">small</div>
        <div class="size">1.333rem</div>
        <div class="text">The quick fox jumps</div>
    </div>
    <div class="element element--9">
        <div class="tag"></div>
        <div class="size">1.111rem</div>
        <div class="text">The quick fox jumps</div>
    </div>
</div>
