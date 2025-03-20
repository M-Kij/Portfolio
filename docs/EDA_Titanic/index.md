# **Eksploracyjna analiza danych dotyczących pasażerów Tytanica**
**2024/12**  

**W tej analizie eksploracyjnej zbadałem dane dotyczące pasażerów Titanica, koncentrując się na kluczowych aspektach, takich jak przeżywalność w zależności od klasy, wieku i płci. Wykorzystałem wizualizacje i statystyki opisowe, aby lepiej zrozumieć strukturę danych oraz czynniki wpływające na przeżycie pasażerów.**

**Technologie: Python, Pandas, Matplotlib**

<a href="EDA_Titanic.ipynb" class="md-button md-button--primary">Pobierz Notebook</a>

<iframe
    id="content"
    src="EDA_Titanic.html"
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