# Importer Fideli sans perdre les dossiers

Ce dossier contient déjà un dépôt Git local prêt pour GitHub Desktop. N’utilisez pas « Upload files » dans le navigateur pour sélectionner les fichiers un par un : cette méthode a aplati `app/` dans votre essai précédent.

1. Sur Windows, clic droit sur le ZIP > **Extraire tout**. Vous obtenez le dossier `fideli-v7-github-desktop`.
2. Ouvrez **GitHub Desktop**, connectez votre compte GitHub, puis **File > Add local repository > Choose**. Sélectionnez le dossier `fideli-v7-github-desktop` extrait.
3. Cliquez **Publish repository**. Vous pouvez laisser **Keep this code private** coché.
4. Sur GitHub, la première page du dépôt doit montrer les dossiers `app`, `components`, `lib`, `supabase` à côté de `package.json`. Ouvrez `app` : `layout.tsx` et `page.tsx` doivent s’y trouver.
5. Dans Vercel, importez **ce nouveau dépôt**. Choisissez Next.js et **Root Directory `./`**. Ajoutez les variables décrites dans `README.md`.

Si GitHub Desktop indique que le dossier est introuvable, sélectionnez le dossier extrait lui-même, et non le ZIP ni un fichier à l’intérieur.

Pour la base de données, lisez `README.md` avant d’inscrire de vrais clients.
