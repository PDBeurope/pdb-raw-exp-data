# PDBe Raw Experimental Data web component

This repository is the codebase for a Polymer component that displays "raw" (i.e. unprocessed) experimental data when available for a specific PDB entry. 
The web component is used by the [Protein Data Bank in Europe (PDBe)](https://pdbe.org) on its entry pages.

## Quick start

1.) Download this repository
```
git clone https://github.com/PDBeurope/pdb-raw-exp-data.git
```

2.) Import the component and its dependency

```
<script src="bower_components/webcomponentsjs/webcomponents-lite.js"></script>
<link rel="import" href="raw-exp-data.html">
```

3.) Add the web component for a specified PDB entry

```
<raw-exp-data style="max-width: 50%;" pdbid="4WEQ"></raw-exp-data>
```

## Authors

* **Mihaly Varadi** - *Initial work* - [mvaradi](https://github.com/mvaradi)

## License

This project is licensed under the EMBL-EBI License - see the [LICENSE](LICENSE) file for details
