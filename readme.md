spécification
Votre site Web doit répondre aux exigences suivantes.

Pages . Votre site Web doit comporter au moins trois pages: une pour la recherche Google, une pour la recherche d'images Google et une pour la recherche avancée Google.
Sur la page de recherche Google, il devrait y avoir des liens dans le coin supérieur droit de la page pour accéder à la recherche d'images ou à la recherche avancée. Sur chacune des deux autres pages, il devrait y avoir un lien en haut à droite pour revenir à la recherche Google. 
Texte de la requête . Sur la page de recherche Google, l'utilisateur doit pouvoir saisir une requête, cliquer sur "Recherche Google" et être redirigé vers les résultats de recherche Google pour cette page.
Comme celle de Google, votre barre de recherche doit être centrée avec des coins arrondis. Le bouton de recherche doit également être centré et se trouver sous la barre de recherche.
Rechercher des images . Sur la page Recherche d'images Google, l'utilisateur doit pouvoir saisir une requête, cliquer sur un bouton de recherche et être redirigé vers les résultats de recherche Google Image pour cette page.
Requête avancée . Sur la page de recherche avancée de Google, l'utilisateur doit être en mesure de fournir une entrée pour les quatre champs suivants (tirés des propres options de recherche avancée de Google )
Rechercher des pages contenant… "tous ces mots:"
Rechercher des pages contenant… "ce mot ou cette expression exacte:"
Rechercher des pages contenant… "l'un de ces mots:"
Rechercher des pages avec… "aucun de ces mots:"
Apparence . Comme la page de recherche avancée de Google, les quatre options doivent être empilées verticalement et tous les champs de texte doivent être alignés à gauche.
Conformément au propre CSS de Google, le bouton «Recherche avancée» doit être bleu avec du texte blanc. Lorsque vous cliquez sur le bouton «Recherche avancée», l'utilisateur doit être dirigé vers la page de résultats de recherche pour sa requête donnée.
Chanceux . Ajoutez un bouton "J'ai de la chance" à la page principale de recherche Google. Conformément au comportement de Google, le fait de cliquer sur ce lien devrait diriger les utilisateurs directement vers le premier résultat de recherche Google pour la requête, en contournant la page de résultats normale.
Esthétique . Le CSS que vous écrivez doit correspondre le mieux possible à l'esthétique de Google.
Conseils
Pour déterminer ce que devraient être les noms de paramètres, vous êtes invités à faire des recherches sur Google et à regarder l'URL résultante. Il peut également être utile d'ouvrir l'inspecteur «Réseau» (accessible dans Google Chrome en choisissant Affichage -> Développeur -> Outils de développement) pour afficher les détails des demandes que votre navigateur fait à Google.
Tout <input>élément (si son typeest text, submit, numberou autre chose) peut avoir nameet valueattributs qui deviendront des paramètres GET lorsqu'un formulaire est soumis.
Vous pouvez également trouver utile de consulter le code HTML de Google pour répondre à ces questions. Dans la plupart des navigateurs, vous pouvez faire un contrôle-clic ou un clic droit sur une page et choisir «Afficher la source de la page» pour afficher le code HTML sous-jacent de la page.
Pour inclure un champ de saisie dans un formulaire que les utilisateurs ne peuvent ni voir ni modifier, vous pouvez utiliser un champ de saisie «masqué» .
Comment soumettre
Attendez! Si vous avez déjà soumis et reçu une note de passage pour la version précédente du projet 0 (page d'accueil), veuillez vous arrêter ici. Vous avez déjà reçu un crédit d'équivalence pour ce projet, et vous ne devez pas soumettre cette mission, car elle n'aura aucun impact sur votre progression dans le cours et ne fera donc que ralentir nos niveleuses!

Visitez ce lien , connectez-vous avec votre compte GitHub et cliquez sur Autoriser cs50 . Ensuite, cochez la case indiquant que vous souhaitez autoriser le personnel du cours à accéder à vos soumissions, puis cliquez sur Rejoindre le cours .
Installez Git et, éventuellement, installezsubmit50 .
Lorsque vous soumettez votre projet, le contenu de votre web50/projects/2020/x/searchsuccursale doit correspondre à la structure de fichier du code de distribution décompressé tel que reçu à l'origine. C'est-à-dire que vos fichiers ne doivent pas être imbriqués dans d'autres répertoires de votre propre création ( searchou project0, par exemple). Votre branche ne doit pas non plus contenir de code provenant d'autres projets, seulement celui-ci. Le non-respect de cette structure de fichier entraînera probablement le rejet de votre soumission.

À titre d'exemple, pour ce projet, cela signifie que si le personnel de notation visite https://github.com/me50/USERNAME/blob/web50/projects/2020/x/search/index.html(où USERNAMEest votre propre nom d'utilisateur GitHub tel que fourni dans le formulaire ci-dessous), votre soumission index.htmlpour ce projet devrait être ce qui apparaît. Si ce n'est pas le cas, réorganisez votre référentiel selon vos besoins pour correspondre à ce paradigme.

Si vous avez installé submit50, exécutez
submit50 web50/projects/2020/x/search
Sinon, en utilisant Git, transférez votre travail vers https://github.com/me50/USERNAME.git, où se USERNAMEtrouve votre nom d'utilisateur GitHub, sur une branche appelée web50/projects/2020/x/search.

Enregistrez un screencast d'une durée maximale de 5 minutes, dans lequel vous démontrez la fonctionnalité de votre projet. Votre barre d'URL doit rester visible tout au long de votre démonstration du projet. Assurez-vous que chaque élément de la spécification ci-dessus est illustré dans votre vidéo. Il n'est pas nécessaire de montrer votre code dans cette vidéo, juste votre application en action; nous examinerons votre code sur GitHub. Téléchargez cette vidéo sur YouTube (comme non répertoriée ou publique, mais pas privée) ou ailleurs. Dans la description de votre vidéo, vous devez horodater l'endroit où votre vidéo montre chacun des sept (7) éléments de la spécification. Ce n'est pas facultatif , les vidéos sans horodatage dans leur description seront automatiquement rejetées.
Soumettez ce formulaire .
Vous pouvez ensuite aller sur https://cs50.me/cs50w pour voir votre progression actuelle!

Remarque IMPORTANTE concernant votre carnet de notes sur cs50.me/cs50w ! Peu de temps après le début de chaque année civile (nous estimons au cours de la semaine du 11 janvier 2021), nous actualisons généralement tous nos cahiers de notes. Tout votre travail de 2020 sera enregistré et reporté , mais votre carnet de notes peut apparaître temporairement vide ou indisponible jusqu'à ce que vous ayez soumis un travail en 2021 qui a été noté et vous a été retourné par CS50 Bot. Alors ne vous inquiétez pas!

Si vous terminez CS50W pendant les derniers jours de décembre 2020, il est très important que vous réclamiez votre certificat CS50 gratuit avant que cette réinitialisation du carnet de notes n'ait lieu, alors ne tardez pas! (Les certificats vérifiés ne sont pas affectés par cela.)