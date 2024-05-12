# lock-content-shopify
With the help of this code you can lock your content (Copy/paste lock, not open inspect/ lock side click of mouse) in shopify, wordpress or any CMS plateform. you just need to paste this code in the backend

here is javascript code

    // Disable right-click context menu
    window.addEventListener('contextmenu', function (e) {
      e.preventDefault();
    });

    // Disable text selection
    document.addEventListener('selectstart', function (e) {
      e.preventDefault();
    });
