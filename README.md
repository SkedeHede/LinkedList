# PlaylistLinkedList

Et C-program der arbejder med en enkeltkædet linked list til at håndtere en playliste af sangtitler.  
Programmet læser en tekstfil med sangtitler, gemmer dem i en linked list, foretager ændringer  
(sletning og indsættelse) og gemmer den opdaterede playliste i en ny fil.  
(Kodekilder: `main.c`, `singly_linked_list.c`, `singly_linked_list.h`)

---

## Brug

```bash
gcc .\main.c .\singly_linked_list.c -o .\LinkedList.exe
./playlist
```

### Forventet inputfil:

- playlist.txt – Indeholder én sangtitel pr. linje (maks 60 tegn inkl. terminator).

Programmet genererer automatisk:

- playlist-out.txt – Den opdaterede playliste efter ændringer.

## Filer
- main.c
- singly_linked_list.c
- singly_linked_list.h
- playlist.txt
- playlist-out.txt (genereres automatisk)
