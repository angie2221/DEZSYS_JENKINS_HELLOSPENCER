# Protokoll Angelie Sharma CI/CD Jenkins Pipeline

Um Jenkins zu installieren und zu initialisieren bin ich der Anleitung in der Angabe gefolgt.
## EKü
### Erstellen einer normalen Pipeline
  1. Als erstens erstellen wir ein eine Pipeline indem wir auf new Item -> new Pipeline gehen. In Script-Fenster oben gibt es die Option einen Sample-Pipeline Script zu verwenden.
  <img width="1361" height="628" alt="image" src="https://github.com/user-attachments/assets/f39c2f46-b2e1-403f-b0c6-9c03a9c27603" />
  2. Build erstellen und ausführen
  <img width="859" height="464" alt="image" src="https://github.com/user-attachments/assets/aee37332-0cba-4955-ae09-ac174ceaca7e" />
  <img width="966" height="465" alt="image" src="https://github.com/user-attachments/assets/5ec49846-c1da-4863-bab3-271d36d03436" />
### Erstellen einer Pipeline mit Einbindung über Github Repo
  1. Selber Vorgang wie bei 1., kleinere Umstellungen.
  <img width="1388" height="688" alt="image" src="https://github.com/user-attachments/assets/7c8e8640-1949-4988-9582-e28a107a826f" />
  <img width="1210" height="123" alt="image" src="https://github.com/user-attachments/assets/f1c6ec02-2472-4ef6-8ff0-656872b1b298" />
  !! Originell steht da "master" statt main! Wichtig umzustellen.
  <img width="1380" height="126" alt="image" src="https://github.com/user-attachments/assets/ab047d5c-cad2-4e58-8041-372de25ee050" />
  2. Lightweight Checkout ausschalten
  Hat bei mir fehlgeschlagene Builds gelöst.
  <img width="1339" height="537" alt="image" src="https://github.com/user-attachments/assets/c654d340-db46-4562-9c8f-3e3827755daa" />
