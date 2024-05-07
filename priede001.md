---
sidebar_position: 8
---
# Priedes kodu piemēri

## Metamais kauliņš

Metamais kauliņš ar 6 skaldnēm izmantojot funkciju `jukums`

```priede
sk a : jukums(1;6)

ja a = 6{
    izvade("Uz metamā kauliņa uzmestā vērtība ir 6")
}
ja a = 5{
    izvade("Uz metamā kauliņa uzmestā vērtība ir 5")
}
ja a = 4{
    izvade("Uz metamā kauliņa uzmestā vērtība ir 4")
}
ja a = 3{
    izvade("Uz metamā kauliņa uzmestā vērtība ir 3")
}
ja a = 2{
    izvade("Uz metamā kauliņa uzmestā vērtība ir 2")
}
ja a = 1{
    izvade("Uz metamā kauliņa uzmestā vērtība ir 1")
}
```

## Paroles ievadīšana un pārbaudīšana

```priede
sk Parole : ievade()
ja Parole = "123"{
    izvade("Parole ir pareiza")
}
citādi{
    izvade("Parole nav pareiza")
}
```

