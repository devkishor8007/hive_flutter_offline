# Hive Offline Storage in Flutter

Using Hive to store the data as a Offline.
Hive is a lightweight and blazing fast key-value database written in pure Dart.

## Getting Started

### Before clone the repo, you must have flutter on your device.
 
    Fork this repo 
    $ git clone https://github.com/<username_github>/hive_flutter_offline

### Remember to update all the packages...
    $ flutter clean
    $ flutter pub get
    
### Run the app
     f5 or click on RUN

##

### Pacakge That I use in this project
    hive
    hive_flutter
    path_provider

### Usage

#### You can use Hive just like a map. It is not necessary to await Futures.

    var box = Hive.box('myBox');

    box.put('name', 'David');

    var name = box.get('name');

    print('Name: $name');
