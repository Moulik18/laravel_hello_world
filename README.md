# Laravel Quick Start

This is a basic guide to get you started with a new Laravel project.

## Step 1: Install Laravel

Make sure you have [Composer](https://getcomposer.org/) installed.

```bash
laravel new hello_world
cd hello_world

<button onclick="copyToClipboard('laravel new hello_world\ncd hello_world')">Copy</button>

<details>
  <summary>Copy Instructions</summary>
Click the "Copy" button.
Open your terminal.
Paste the copied command and press Enter.
</details>
<script>
    function copyToClipboard(text) {
        var textarea = document.createElement('textarea');
        textarea.value = text;
        document.body.appendChild(textarea);
        textarea.select();
        document.execCommand('copy');
        document.body.removeChild(textarea);
        alert('Command copied to clipboard!');
    }
</script>
