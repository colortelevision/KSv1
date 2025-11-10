# KSv1
Krimpsoft OS v1

## How to add a new app

To add a new app, you need to add a new `div` with the class `icon` inside the `#desktop` div in `index.html`.

Here's a template for a new app icon:

```html
<div
    class="icon"
    onclick="openWindow('app-id', 'App Title', '/path-to-app/')"
>
    <img
        src="https://win98icons.alexmeub.com/icons/png/icon-name.png"
        alt="App icon"
    />
    <div>App Name</div>
</div>
```

*   Replace `app-id` with a unique ID for your app.
*   Replace `App Title` with the title that will appear in the window header.
*   Replace `/path-to-app/` with the actual path to your app's content.
*   Replace `https://win98icons.alexmeub.com/icons/png/icon-name.png` with the URL of your app's icon.
*   Replace `App Name` with the name that will appear under the icon on the desktop.