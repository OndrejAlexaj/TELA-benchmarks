# TELA-benchmarks
Benchmarks obtained by:
```
    ./gen.sh formulae_files ltl3tela     // creates outputs_TIMESTAMP dir with automata and classification file (.csv)
    ./filter.sh classification_file      // takes classification of automata and produces filtered.csv (classification) and creates folder 'filtered' with respective .hoa files
```
Filtering is done as follows: 
1. remove automata with empty languages,
2. remove deterministic automata,
3. remove inherently weak automata,
4. TODO justify last step in filter.sh pipeline