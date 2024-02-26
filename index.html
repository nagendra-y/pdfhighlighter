<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8" />
    <title>PDF.js Example</title>
    <style>
        #pdfViewer {
            width: 100%;
            height: 100vh; /* Occupy full viewport height */
            border: none;
        }
    </style>
</head>

<body>
    <iframe id="pdfViewer" src="/pdfhighlighter/viewer.html?file=example.pdf" width="100%" height="100%" style="border: none;"></iframe>

<script>

function showSelectedPage(selectedPageNumber) {
    const iframeDocument = document.getElementById('pdfViewer').contentWindow.document;
    const pages = iframeDocument.getElementsByClassName('page');

    for (let i = pages.length - 1; i >= 0; i--) {
        const pageNumber = pages[i].getAttribute('data-page-number');

        if (pageNumber != selectedPageNumber) {
            pages[i].remove();
        }
    }
}


function searchAndHighlightOnPage(pageNumber, searchText) {
    const iframeDocument = document.getElementById('pdfViewer').contentWindow;
    iframeDocument.addEventListener('DOMContentLoaded', function() {
        // Dispatch a command to render a specific page
        // Wait for the page to be rendered before searching and highlighting
        setTimeout(function() {
            iframeDocument.PDFViewerApplication.eventBus.dispatch('find', {
caseSensitive: false,
    findPrevious: undefined,
        highlightAll: true,
        phraseSearch: true,
        query: searchText
        });
        
           showSelectedPage(pageNumber);
        }, 1000); // Adjust the delay as needed to ensure the page is rendered before searching
    });
}

// Example usage:
searchAndHighlightOnPage(2, 'A stack is an abstract data type frequently used in computer science. A stack of objects has the property that the last object placed on the stack will be the first object removed. This property is commonly referred to as last in, first out queue, or a LIFO. Several operations are defined on stacks. Two of the most important are PUSH and POP. PUSH adds an element at the top of the stack. POP, in contrast, reduces the stack size by one by removing the last element at the top of the stack');

</script>
</body>

