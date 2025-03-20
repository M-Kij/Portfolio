# **Eksploracyjna analiza danych portalu rekrutacyjnego JustJoin.IT**
**2025/03**  

**W ramach tego projektu przeprowadziłem szczegółową eksploracyjną analizę danych (EDA) dotyczących ofert pracy zamieszczanych na JustJoinIT – jednej z czołowych platform rekrutacyjnych dla branży IT w Polsce. Zbiór danych pochodzi z Kaggle i obejmuje oferty gromadzone codziennie w okresie od 23 października 2021 r. do 25 września 2023 r.**

**Celem analizy było zrozumienie kluczowych trendów na rynku pracy IT, takich jak popularność poszczególnych kompetencji, zakresy wynagrodzeń, preferowane formy zatrudnienia oraz wymagania pracodawców. Wykorzystałem różnorodne techniki wizualizacji oraz statystyki opisowe, aby przedstawić najważniejsze wnioski i dostarczyć wartościowych informacji dla specjalistów IT oraz osób zainteresowanych rynkiem pracy w tej branży.**

**Technologie: Python, Pandas, JSON, NumPy, Plotly, Matplotlib, ITables**

<a href="EDA_JustJoinIT.ipynb" class="md-button md-button--primary">Pobierz Notebook</a>

<iframe
    id="content"
    src="EDA_JustJoinIT.html"
    width="100%"
    style="border:1px solid black;overflow:hidden;"
></iframe>
<script>
function resizeIframeToFitContent(iframe) {
    iframe.style.height = (iframe.contentWindow.document.documentElement.scrollHeight + 50) + "px";
    iframe.contentDocument.body.style["overflow"] = 'hidden';
}
window.addEventListener('load', function() {
    var iframe = document.getElementById('content');
    resizeIframeToFitContent(iframe);
});
window.addEventListener('resize', function() {
    var iframe = document.getElementById('content');
    resizeIframeToFitContent(iframe);
});
</script>