# Laravel Quick Start

This is a basic guide to get you started with a new Laravel project.

## Step 1: Install Laravel

Make sure you have [Composer](https://getcomposer.org/) installed.

laravel new your-project-name
cd your-project-name

<button id="copyButton" class="copy-button" data-clipboard-text="laravel new your-project-name
cd your-project-name">Copy</button>

<style>
    .copy-button {
        display: inline-block;
        padding: 10px 15px;
        font-size: 14px;
        font-weight: bold;
        color: #fff;
        background-color: #3498db;
        border: none;
        border-radius: 4px;
        cursor: pointer;
    }

    .copy-button:hover {
        background-color: #2980b9;
    }
</style>

<script src="https://cdnjs.cloudflare.com/ajax/libs/clipboard.js/2.0.8/clipboard.min.js"></script>
<script>
    var clipboard = new ClipboardJS('#copyButton');

    clipboard.on('success', function (e) {
        alert('Command copied to clipboard!');
        e.clearSelection();
    });

    clipboard.on('error', function (e) {
        console.error('Error copying command to clipboard:', e);
    });
</script>
