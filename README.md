# MagicMirror² DadJokeAPI module
This is a module for `MagicMirror²`; the purpose of the module is to show you jokes from i can haz dad joke .

## Installation
1.  Clone this repository into your MagicMirror `modules` folder.
2.  Edit your configuration file under `config/config.js` with the following configuration.
```
{
    module: 'MMM-DadJokeAPI',
    position: 'middle_center',
    config: {
        fetchInterval: 600000
    }
}
```

## Configuration options

| Option                 | Description
|------------------------|-----------
| `fetchInterval`| How often (in milliseconds) a new joke should be fetched.<br><br> **Type:** `number` <br>**Default value:** `10 * 1000`


#### Credits
MagicMirror²:   [MagicMirror²](https://github.com/MichMich/MagicMirror)   
JokeAPI:    [JokeAPI](https://icanhazdadjoke.com/)
