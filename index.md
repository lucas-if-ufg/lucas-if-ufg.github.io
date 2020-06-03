<script type="text/x-mathjax-config">
MathJax.Hub.Config({
tex2jax: {
inlineMath: [['$','$'], ['\\(','\\)']],
processEscapes: true},
jax: ["input/TeX","input/MathML","input/AsciiMath","output/CommonHTML"],
extensions: ["tex2jax.js","mml2jax.js","asciimath2jax.js","MathMenu.js","MathZoom.js","AssistiveMML.js", "[Contrib]/a11y/accessibility-menu.js"],
TeX: {
extensions: ["AMSmath.js","AMSsymbols.js","noErrors.js","noUndefined.js"],
equationNumbers: {
autoNumber: "AMS"
}
}
});
</script>

## Bem-vindo!
Este website foi criado para divulgar os resultados de minha pesquisa relacionadas ao modelo de Bell-Lavis. Sinta-se a 
vontade para explorar essa gama de resultados.

## Pesquisas

### Modelo de Bell-Lavis 

Este modelo foi criado por Bell e Lavis para representar o comportamento orientacional das ligações de hidrogênio nas
moléculas de água [Bell1970](https://iopscience.iop.org/article/10.1088/0305-4470/3/5/015). Vário estudos foram realizados para esse
modelo como aproximações de campo médio [Bell1970](https://iopscience.iop.org/article/10.1088/0305-4470/3/5/015),[Lavis1973](http://stacks.iop.org/0022-3719/6/i=9/a=010),
análise de grupo de renormalização [Young1979](http://dx.doi.org/10.1088/0305-4470/12/2/012),[Southern1980](http://dx.doi.org/10.1088/0305-4470/13/1/026), método de variação de clusteres [Buzano2008](https://doi.org/10.1063/1.2919126) e cálculos de Bethe para
Husimi cactus [Barbosa2008](https://link.aps.org/doi/10.1103/PhysRevE.77.051204). Simulações de Monte Carlo também foram realizadas [Fiore2009](https://doi.org/10.1063/1.3253297}),[Simenas2014](https://link.aps.org/doi/10.1103/PhysRevE.90.042124),[Simenas2015](https://doi.org/10.1080/01411594.2014.983509).

Abordamos esse modelo usando simulações entrópicas, futuramente escreverei um tópico para esse tipo de simulação. Com ela podemos obter a densidade de estados conjunta com a qual podemos escrever a probabilidade do sistema estar em uma configuração dependendo da temperatura e dos termos energéticos relacionados a hamiltoniana do sistema como 

\begin{equation}
P(T,\mathcal{H})=\frac{g(\mathcal{H}) e^{-\mathcal{H}/k_BT}}{\sum_{\mathcal{H}} g(\mathcal{H}) e^{-\mathcal{H}/k_BT}},
\end(equation}
onde $k_B$ é a constante de Boltzmann e g(\mathcal{H}) é a densidade de estados.
Através dessa quantidade podemos obter as configurações que maximizam a probabilidade dada uma temperatura. Colocamos as configurações em um vídeo para evidenciar a mudança com o aumento da temperatura. O resultado pode ser visto em [fases para o modelo de Bell-Lavis](Fases_bl.html).

## Notícias

Em breve posto novidades.

## Contato

Lucas Ferreira - ferreira_s_lucas@ufg.br
Universidade Federal de Goiás
Instituto de Física
