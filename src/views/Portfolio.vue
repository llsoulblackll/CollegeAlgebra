<template>
    <div class="math-holder">
        <div id="e1" class="e" style="display: block;">
            <b>Ejercicio 01:</b>
            <br>
            a)
            $$4x^2 + 16x - 9 = 0$$ 
            b)
            $$w^2 = 3(w - 1)$$
            c)
            $$z^2 + 5z + 3 = 0$$
            d)
            $$x^2 - \sqrt{5}x + 1 = 0$$
        </div>
        <div id="e2" class="e">
            <b>Ejercicio 02:</b>
            $$2x + \sqrt{x + 1} = 8$$
            Paso 1:
            $$-2x + 2x + \sqrt{x + 1} = 8 - 2x \; \implies \; \sqrt{x + 1} = 8 - 2x $$
            $$x + 1 = (8 - 2x)^2 \; \implies \; x + 1 = 4x^2 - 32x + 64$$
            Paso 2:
            $$4x^2 - 33x + 63 = 0$$
            a)
            $$x = \frac{-\left(-33\right)+\sqrt{\left(-33\right)^2- 4(4)(63)}}{2(4)}$$
            $$x = \frac{-\left(-33\right)+\sqrt{1089 - 1008}}{2(4)} \; \implies \; \frac{-\left(-33\right)+\sqrt{81}}{2(4)}$$
            $$x = \frac{33 + 9 }{8} \; \implies \; \frac{42}{8}$$
            $$x = {21\over4} \; \lor \; 5.25$$
            b)
            $$x = \frac{-\left(-33\right)-\sqrt{\left(-33\right)^2- 4(4)(63)}}{2(4)}$$
            $$x = \frac{-\left(-33\right)-\sqrt{1089 - 1008}}{2(4)} \; \implies \; \frac{-\left(-33\right)-\sqrt{81}}{2(4)}$$
            $$x = \frac{33 - 9}{8} \; \implies \; \frac{24}{8}$$
            $$x = 3$$
        </div>
        <div id="e3" class="e">
            <b>Ejercicio 03 \(pie^3\):</b>
            $$x(x + 9)(x - 4) = 180$$
            Paso 1 (Distributiva):
            $$x(x^2 + 5x - 36) = 180$$
            Paso 2:
            $$x^3 + 5{x^2} - 36x = 180 \; \implies \; x^3 + 5{x^2} - 36x - 180 = 180 - 180$$
            Paso 3:
            $$x^3 + 5{x^2} - 36x - 180 = 0$$
            Paso 4:
            \begin{array}{r|rrrr}  &amp; 1 &amp; -4 &amp; 5 &amp; -2\\ 2 &amp;  &amp; 2 &amp; -4 &amp; 2\\ \hline  &amp; 1 &amp; -2 &amp; 1 &amp; 0\end{array}
        </div>
        <div id="e4" class="e">
            Ejercicio 04: 
            $${4x\over2x + 3}>2$$
            Paso 1: 
            $${4x\over2x + 3} - 2 > 2 - 2 \; \implies \; {4x\over2x + 3} - 2 > 0$$
            Pase 2: 
            $${4x - 4x - 6\over2x+3} > 0 \; \implies \; {-6\over2x + 3} > 0 \; \implies \; -{6\over2x+3} > 0$$
            Paso 3 (Invertimos el signo): 
            $$-1(-{6\over2x + 3}) > -1(0) \; \implies \; {6\over2x + 3} &lt; 0$$
            Paso 4 (Hallamos el valor de modo que el denominador sea 0):
            $$2x + 3 = {0} \; \implies \; x = {-3\over2}$$
            Paso 5 (Conjunto Solución):
            $$C.S = [-\infty;\infty]-\{ {-3\over2}\}$$
        </div>
        <div id="e5" class="e">
            <b>Ejercicio 05:</b>
            $$R = 20x$$
            $$C = 2000 + 8x + 0.0025{x^2}$$
            $$Ganancia = R - C$$
            Paso 1:
            $$20x - (2000 + 8x + 0.0025{x^2}) \geqslant 2400$$
            Paso 2:
            $$20x -0.0025{x^2} - 8x - 2000 \geqslant 2400 \; \implies \; -0.0025{x^2} + 12x - 2000 \geqslant 2400$$
            Paso 3 (Invertimos el signo):
            $$-1(-0.0025{x^2} + 12x - 2000) \geqslant -1(2400) \; \implies \; 0.0025{x^2} - 12x + 2000 \leqslant -2400$$
            Paso 4 (Igualamos a 0):
            $$0.0025{x^2} - 12x + 2000 + 2400 \leqslant -2400 + 2400 \; \implies \; 0.0025{x^2} - 12x + 4400 \leqslant 0$$
            Paso 5 (Hallamos las 2 posibles soluciones de la ecuacion):
            <br>
            a)
            $$x = {-(-12) + \sqrt{ {(-12)^2} - 4(0.0025)(4400)}\over2(0.0025)}$$
            $$x = {12 + \sqrt{100}\over0.005}$$
            $$x = {22\over0.005}$$
            $$x = 4400$$
            b)
            $$x = {-(-12) - \sqrt{ {(-12)^2} - 4(0.0025)(4400)}\over2(0.0025)}$$
            $$x = {12 - \sqrt{100}\over0.005} \; \implies x = {12 - 10\over0.005} \;$$
            $$x = {2\over0.005}$$
            $$x = 400$$
            $$$$
            Paso 6 (Resultado):
            $$C.S. = [400, 4400]$$
        </div>
    </div>
</template>
<script>
export default {
    mounted(){
        /*this.mathJax = document.createElement('script');
        this.mathJax.id = 'mathJax';
        this.mathJax.src = "https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.5/MathJax.js?config=TeX-MML-AM_CHTML";
        document.head.appendChild(this.mathJax);
        */
       MathJax.Hub.Queue(["Typeset", MathJax.Hub]);
    }
}
</script>