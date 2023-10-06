Si realizzi un'applicazione multithreaded che, dato un testo cifrato riesce a trovare 
la chiave mediante un metodo di "forza bruta"(ricerca esaustiva della soluzione).

Il testo è stato cifrato usando Advanced Encryption Standard (AES). Nello specifico, la chiave usata
per cifrare il file è un intero positivo compreso tra 0 e Integer.MAX_VALUE. 

Visto che AES accetta una chiave composta da 16 caratteri, il numero deve essere convertito in testo 
aggiungenfo una serie di zeri all'inizio della stringa. Ad esempio, se vogliamo usare la chiave 123456
dobbiamo trasformarla nel testo "000000000123456"

Il testo se correttamente decriptato conterrà al suo interno la stringa "SISOP" (può contenere anche altro testo)

NB: Java fornisce delle librerie  per la crittografia e la decrittografia attraeverso il framework Java
Crytographic Extension(JCE), che implementa gli algoritmi di critografia standard come AES, DES, DESede e RSA. 