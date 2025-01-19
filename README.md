# Firefox-Custom-
A userChrome.css theme to bring Arc Browser look on Windows to Firefox. Work with Windows, Linux and macOS 

<h1 align="center">
  🦊 StarUpFox UPDATED
</h1>

<h2 align="center">
  A Firefox user CSS theme that looks similar to Chrome.
</h2>

![Uploading imagen.png…](https://github.com/user-attachments/assets/18d97e08-f3dc-4e88-8e96-7316f6106257)



## 🚀 Getting Started

To start using MaterialFox UPDATED, follow these steps:

1. **Open** Firefox and type `about:config` in the address bar, then press <kbd>Enter</kbd>.
2. If a warning page appears, **click** `Accept the Risk and Continue` to access the `about:config` page.
3. **Search** for the following preferences using the search bar at the top of the `about:config` page, and **ensure** the following preferences are `true`:

   - `toolkit.legacyUserProfileCustomizations.stylesheets`
   - `svg.context-properties.content.enabled`
   - `layout.css.color-mix.enabled`

4. **Type** `about:support` in the address bar and press <kbd>Enter</kbd>.
5. **Scroll down** to the `Profile Folder` section and **click** `Open Folder`.
6. **Download** the `chrome.zip` file from the [**latest release**](https://github.com/edelvarden/material-fox-updated/releases/latest).
7. **Extract** the contents of `chrome.zip` into your Firefox profile directory.
8. **Restart** Firefox to apply the changes.


## 🎨 Manual Customization

You can **apply** visual design changes by adding some `about:config` customization options (preferences).

To **set** a preference, **type** `about:config` in the address bar and press <kbd>Enter</kbd>.

To **enable** a preference:

1. **Create** a custom boolean preference by typing the preference name and **clicking** the plus button. For example, `userChrome.ui-chrome-refresh` enables the new Chrome design.

To **disable** a preference:

1. **Search** for it by name and **delete** the preference or toggle its state to `false`.

5. Save the file and restart Firefox to apply changes.

Project structure

```plaintext
Firefox-Custom/
├── policies/
│   └── policies.json
├── preferences/
│   └── user.js
└── chrome/
    └── userChrome.css

```
