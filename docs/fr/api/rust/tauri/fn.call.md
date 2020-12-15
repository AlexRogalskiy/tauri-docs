---
title: "fn.call"
---

# Function [tauri](/docs/api/rust/tauri/index.html)::​[call](/docs/api/rust/tauri/)

    pub fn call<T: 'static>(
        webview: &mut WebView<T>, 
        command: String, 
        args: Vec<String>, 
        callback: String, 
        error: String
    )

Appelle la commande donnée et évalue sa sortie à la promesse JS décrite par la fonction `callback` et `error`.
