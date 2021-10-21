# TP2-Programmation-embarqu-et-mobile-

" 02.1 "
Question 1 ==> La deuxième activité est ajoutée en tant que classe Java, le fichier de présentation (layout) XML est créé et le fichier AndroidManifest.xml est modifié pour déclarer une deuxième activité.

Question2 ==>Le deuxième fichier de mise en page (layout) XML d'activité est supprimé.

Question 3 ==>new Intent(String action, Uri uri)

Question4  ==> En tant qu'action d'intention (Intent)

"2.2" 
Question1 ==> Le compteur est réinitialisé à 0 et l' EditText ne contient plus le texte que vous avez entré.
Question 2 ==> Android arrête votre activité en appelant onPause(), onStop() et onDestroy(), puis redémarre l'opération en appelant onCreate(), onStart() et onResume().
Question 3 ==> onSaveInstanceState() est appelée avant la méthode onResume().
Question 4 ==> onPause() ou onStop()
"2.3" 

Question 1 ==> Quelle méthode de constructeur utilisez-vous pour créer une intention implicite de lancer une application de caméra : #new Intent()

Question2 ==> Ne spécifiez pas l'activité ou autre composant spécifique à lancer.

Question 3 ==>  Quelle action Intention utilisez-vous pour prendre une photo avec une application appareil photo : #Intent takePicture = new Intent(MediaStore.ACTION_IMAGE_CAPTURE);
