diff --git a/README.md b/README.md
index e69de29bb2d1d6434b8b29ae775ad8c2e48c5391..2bbf085a8b8d5e3ed356eb1649aef10a3cfb4613 100644
--- a/README.md
+++ b/README.md
@@ -0,0 +1,24 @@
+# Video Translator for My AI
+
+Cette application permet de coller un lien vers une vidéo (YouTube, TikTok...), de télécharger l'audio, de le transcrire grâce à Whisper et de générer un message à envoyer à votre IA personnelle.
+
+## Installation
+
+Assurez-vous d'utiliser Python 3.10 ou plus.
+
+```bash
+pip install -r requirements.txt
+sudo apt-get update && sudo apt-get install -y ffmpeg
+```
+
+## Utilisation
+
+```bash
+python app.py
+```
+
+Une interface Gradio s'ouvre alors dans votre navigateur.
+
+## Déploiement sur Hugging Face Spaces
+
+Créez un nouvel espace Gradio et chargez les fichiers de ce dépôt. Les dépendances listées dans `requirements.txt` seront installées automatiquement.
