# sharex uploader By PHP

PHP-based ShareX Custom uploader, easy to setup and use.

# Potrebné
PHP Server (8.0+ recommended)
# Inštálacia
<h2>- Server</h2>
Vymeň CHANGEME v upload.php Nejakou bezpečným kľúčom
a v sharex.sxcu RequestURL na URL kde máš súbor upload.php.
<h2>- Client</h2>
Importni sharex.sxcu do tvojej ShareX app.
Uisti sa že kľúče sa zhodujú v upload.php.
<h2>- Uisti sa</h2>
if you using Cloudflare make sure you check your plan's HTTP POST limit (Cloudflare Docs)
Adjust upload_max_filesize, post_max_size values in your PHP installation
