# mesureslab
cours

# MesuresLab

MesuresLab est le projet support du TP Git et GitHub du BTS CIEL IR.

Le programme évoluera progressivement jusqu'à la version 1.0. Les fichiers de
ce dossier constituent uniquement le point de départ du TP.

## Lancement

```powershell
python app.py
```

"""MesuresLab V0.1 : saisir et afficher une tension."""


def main():
    tension = float(input("Tension mesurée en V : "))
    print(f"Tension enregistrée : {tension:.2f} V")


if __name__ == "__main__":
    main()



