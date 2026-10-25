# Surface Duo Folding App Adaptive Layout Demo

An interactive demo of the Surface Duo dual-screen device, showing how the app inside the screens automatically adapts its layout as the device switches between different form factors. No installation and no internet connection are required — just open it in a browser.

[Online experience](https://lightlytech.github.io/Surface-Duo-UWP/)

## Features

### Three Device Postures

Three buttons are provided on the left side of the page. Clicking one moves the device between postures with a smooth, continuous animation:

- **Open (Unfold)**: the two screens form one large continuous display, and the app fills the whole device in a dual-screen layout.
- **Close**: the reverse of Open — the large display folds back into a single screen.
- **Out-fold**: the right screen folds backward, leaving a single visible screen.

The device starts in the closed posture when the page loads; the animation begins only after a button is clicked.

### Sample App on the Screens

A UWP NavigationView–style sample app runs inside the device screens:

- A navigation pane lets you switch between Home, Search, Account, Mail, and Settings.
- An article list sits in the middle and an article detail view on the right; click a list item to view its content.
- The menu button in the top-left expands or collapses the navigation pane.
- Both light and dark themes are supported.
- When the device is unfolded into dual screens, the list and detail are automatically placed on separate screens; when folded to one screen, the app switches to a single-column view with back-and-forth navigation between list and detail.
- Interacting on one screen (switching sections, selecting an article, expanding the menu) instantly updates the other screen as well.

### Look and Feel

- The title is shown in the top-left corner, with the control buttons in a bar on the left.
- The app background uses a soft multi-color gradient.
- The device and app always fill the screen area completely, without overflowing content or misplaced blank gaps.

## Files

| File | Purpose |
| --- | --- |
| `index.html` | Main demo page with the title, control buttons, and device view |
| `surface duo open.html` | Demo page for the open / close postures |
| `surface duo out fold.html` | Demo page for the out-fold posture |
| `navigateviewer.html` | The sample app running on the device screens |


