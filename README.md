# obsidian-open

Tiny static page that turns an `https://` link into an `obsidian://open` link, so notes can be opened from chats that only allow http(s) links (Telegram).

Link format: `https://<user>.github.io/obsidian-open/#vault=<vault>&file=<path%2Fto%2Fnote>`

The vault and note path are in the URL fragment, so they are never sent to the server. The page builds only `obsidian://open?...` URIs.
