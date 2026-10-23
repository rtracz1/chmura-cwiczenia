# Bezpieczeństwo haseł i kluczy dostępu

Nie wolno zapisywać haseł ani kluczy dostępu w repozytorium, ponieważ osoby mające do niego dostęp mogłyby wykorzystać je do przejęcia kont, danych lub usług. W publicznym repozytorium takie informacje mogą zostać szybko skopiowane także przez automatyczne boty. Samo usunięcie pliku nie wystarcza, ponieważ Git zachowuje historię zmian i poufne dane mogą nadal być dostępne w starszych zatwierdzeniach (commitach), kopiach repozytorium lub forkach. Jeśli hasło lub klucz zostały ujawnione, należy je niezwłocznie zmienić lub unieważnić oraz zadbać o usunięcie sekretu z historii repozytorium tam, gdzie jest to możliwe.

