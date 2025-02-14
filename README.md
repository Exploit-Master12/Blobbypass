(BlobBypass 1) ## [BlobBypass](https://blobbypass.pages.dev/)
BlobBypass is an exploit that allows Chromebook users to bypass website restrictions. It requires [Blobwifi](https://sites.google.com/view/edu-blobe/apps/blobwifi) to function.

- Pages visited in this window will not be saved to your history, but their cookies will be saved.
- You can right-click on the window to go back and forward.
- There's no good way to make the text in the window larger.
- You can't log into non-school accounts.


(2nd version) BlobBypass 2: 



- There is a new version :

Other BlobBypass HTML version: 

```
data:text/html;charset=utf-8,<!DOCTYPE html> <html lang="en"> <head> <meta charset="UTF-8" /> <meta name="viewport" content="width=device-width, initial-scale=1.0" /> <title>Google Iframe VPN</title> <link rel="manifest" href="manifest.json" /> <script> if ("serviceWorker" in navigator) { navigator.serviceWorker .register("/sw.js") .then(() => console.log("Service Worker Registered")) .catch((err) => console.error("Service Worker Error:", err)); } let deferredPrompt; window.addEventListener("beforeinstallprompt", (e) => { e.preventDefault(); deferredPrompt = e; document.getElementById("install-btn").style.display = "block"; }); function installPWA() { if (deferredPrompt) { deferredPrompt.prompt(); deferredPrompt.userChoice.then((choice) => { if (choice.outcome === "accepted") { console.log("PWA installed"); } deferredPrompt = null; }); } } </script> </head> <body> <h1>Blobbypass 2.0 <iframe src="https://www.google.com/webhp?igu=1%22%20width=%22100%%22%20height=%22600px%22%20style=%22border:%20none%22%20%3E%3C/iframe%3E%20%3Cbutton%20id=%22install-btn%22%20onclick=%22installPWA()%22%20style=%22display:%20none%22%20%3E%3C/button%3E%20%3C/body%3E%20%3C/html%3E%20Install%20Button%20and%20Unblocked%20iframe%20made%20by%20Viaan%20Gothivrekar%20%3Ca%20href=%22https://github.com/Exploit-Master12%22%20target=%22_blank%22%20%3E(Exploit-Master12%20on%20Github)%3C/a%20%3E
