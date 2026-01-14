<!doctype html>
<html lang="fr">
<head>
  <meta charset="utf-8" />
  <title>Cours – Introduction à Git & GitHub</title>
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <meta name="description" content="Repository de support pour le cours d'introduction à Git et GitHub." />
  <style>
    body {
      font-family: system-ui, -apple-system, Segoe UI, Roboto, Arial, sans-serif;
      line-height: 1.6;
      margin: 0;
      padding: 0;
    }
    header, main, footer {
      max-width: 900px;
      margin: 0 auto;
      padding: 24px;
    }
    header {
      border-bottom: 1px solid #ccc;
    }
    h1 { margin-top: 0; }
    h2 { margin-top: 32px; }
    code {
      font-family: ui-monospace, SFMono-Regular, Menlo, Consolas, monospace;
      background: #f4f4f4;
      padding: 2px 6px;
      border-radius: 4px;
    }
    pre {
      background: #f4f4f4;
      padding: 12px;
      border-radius: 6px;
      overflow-x: auto;
    }
    ul { margin-left: 20px; }
    .note {
      background: #eef6ff;
      border-left: 4px solid #4c8bf5;
      padding: 12px;
      margin: 16px 0;
    }
    footer {
      border-top: 1px solid #ccc;
      font-size: 0.9em;
      opacity: 0.8;
    }
  </style>
</head>

<body>
  <header>
    <h1>📘 Cours – Introduction à Git & GitHub</h1>
    <p>
      Ce repository sert de <strong>support pratique</strong> pour le cours
      <strong>Git & GitHub</strong>.  
      Il est utilisé pour apprendre les bases du versioning, du travail en équipe
      et de la collaboration avec GitHub.
    </p>
  </header>

  <main>
    <h2>🎯 Objectifs du cours</h2>
    <ul>
      <li>Comprendre ce qu’est le <strong>versioning</strong></li>
      <li>Utiliser Git en ligne de commande</li>
      <li>Collaborer avec GitHub (branches, Pull Requests)</li>
      <li>Découvrir l’écosystème GitHub</li>
    </ul>

    <h2>🧠 Git n’est pas un backup</h2>
    <p>
      Git est un <strong>outil de gestion de versions</strong>, pas un système de sauvegarde.
      Chaque commit représente une <strong>étape volontaire</strong> dans l’historique du projet.
    </p>

    <h2>🔁 Workflow Git utilisé dans ce cours</h2>
    <pre>
Modifier → git add → git commit → git push
                    ↑
                 git pull
    </pre>

    <ul>
      <li><code>git clone</code> : récupérer le projet pour la première fois</li>
      <li><code>git status</code> : savoir où on en est</li>
      <li><code>git add</code> : préparer les changements</li>
      <li><code>git commit</code> : créer une version</li>
      <li><code>git push</code> : partager sur GitHub</li>
      <li><code>git pull</code> : récupérer les changements</li>
    </ul>

    <h2>🌱 Branches & Pull Requests</h2>
    <p>
      Pour travailler à plusieurs sans se gêner, nous utilisons des <strong>branches</strong>
      et des <strong>Pull Requests</strong>.
    </p>
    <ul>
      <li>Une branche sert à <strong>travailler sans casser</strong></li>
      <li>Une Pull Request sert à <strong>proposer et discuter</strong></li>
      <li>Le merge sert à <strong>intégrer le travail</strong></li>
    </ul>

    <h2>🐞 GitHub Issues</h2>
    <p>
      Les <strong>Issues</strong> permettent de discuter d’un problème ou d’une idée
      avant de modifier le code.
    </p>

    <h2>📁 Organisation du repository</h2>
    <ul>
      <li><code>README.html</code> / <code>index.html</code> : description du cours</li>
      <li>Fichiers de test pour les exercices Git</li>
      <li>Branches créées par les étudiants</li>
    </ul>

    <h2>🌐 GitHub Pages</h2>
    <p>
      Ce repository peut être publié via <strong>GitHub Pages</strong>.
      Chaque commit peut mettre à jour le contenu publié.
    </p>

    <div class="note">
      <strong>Astuce :</strong> pour GitHub Pages, le fichier doit s’appeler
      <code>index.html</code> et se trouver à la racine du repository.
    </div>

    <h2>✅ Bonnes pratiques</h2>
    <ul>
      <li>Committez souvent, pour une seule idée</li>
      <li>Écrivez des messages de commit clairs</li>
      <li>Faites toujours un <code>git pull</code> avant de travailler</li>
      <li>Utilisez des branches pour toute modification</li>
    </ul>
  </main>

  <footer>
    <p>
      Repository pédagogique – Cours Git & GitHub  
      <br />
      Objectif : apprendre à travailler proprement, seul et en équipe.
    </p>
  </footer>
</body>
</html>
