```
  _____                        _                       _       _
 |  __ \                      | |                     | |     | |
 | |__) |_ _ _   _ _ __   __ _| |  _ __ ___   ___   __| |_   _| | ___
 |  ___/ _` | | | | '_ \ / _` | | | '_ ` _ \ / _ \ / _` | | | | |/ _ \
 | |  | (_| | |_| | |_) | (_| | | | | | | | | (_) | (_| | |_| | |  __/
 |_|   \__,_|\__, | .__/ \__,_|_| |_| |_| |_|\___/ \__,_|\__,_|_|\___|
              __/ | |
             |___/|_|
                    _             _______ _          _ _
                   | |           |__   __| |        | (_)
                   | |__  _   _     | |  | |__   ___| |_  __ _
                   | '_ \| | | |    | |  | '_ \ / _ \ | |/ _` |
                   | |_) | |_| |    | |  | | | |  __/ | | (_| |
                   |_.__/ \__, |    |_|  |_| |_|\___|_|_|\__,_|
                           __/ |
                          |___/               <info@thelia.net>
```


=== SUMMARY ===
fr_FR:
I)   Installation
II)  Utilisation
III) Intégration

en_US:
I)   Install notes
II)  How to use
III) Integration


# === fr_FR ===

## I)  Installation

### Pour Thelia 2.0

Pour installer le module paypal, téléchargez l'archive de la branche 2.0 et décompressez la dans <dossier de thelia>/local/modules

### Pour Thelia 2.1

Pour installer le module paypal, téléchargez l'archive de la branche master et décompressez la dans <dossier de thelia>/local/modules

## II) Utilisation

Pour utiliser le module paypal, allez dans le back-office, onglet Modules, et activez le module Paypal,
puis cliquez sur "Configurer" sur la ligne de Paypal. Remplissez vos identifants et enregistrez.
Pensez à effectuer quelques commandes factices en mode sandbox ( cochez la case "Activer la sandbox" dans l'onglet
Configurer la sandbox de la page de configuration et enregistrez).

## III) Intégration

Un exemple d'intégration est présent dans <dossier du module>/templates/frontOffice/default
Vous devez réaliser une page présentant une erreur interne nommée gotopaypalfail.html et un page d'annulation de la commande
nommée ordercanceled.html

# === en_US ===

## I)  Installation

### Thelia 2.0

To install the paypal module, download the archive from 2.0 branch uncompress it in <path to thelia>/local/modules

### Thelia 2.1

To install the paypal module, download the archive from master branch uncompress it in <path to thelia>/local/modules

## II) How to use

To use the module, you first need to activate it in the back-office, tab Modules, and click on "Configure" on the line
of paypal module. Enter your paypal login informations and save.
Don't forget to do some fake orders in sandbox mode ( check "Active sandbox mode" box in tab Configure sandbox in the
configuration page, and save ).

## III) Integration

There is an integration example in the directory <module path>/templates/frontOffice/deufault
You must do a page containing a internal error message called gotopaypalfail.html and a order cancel page called ordercanacled.html