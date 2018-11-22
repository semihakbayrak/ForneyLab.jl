# Factor Nodes

### Index
```@index
Modules = [ForneyLab]
Pages = ["factor_nodes.md"]
Order = [:macro, :module, :constant, :type, :function]
```

### Description
```@autodocs
Modules = [ForneyLab]
Private = false
Pages = collect(Iterators.flatten([[joinpath(root[4:end], file) for file in files] for (root, dirs, files) in walkdir("../src/factor_nodes/")]))
Order = [:macro, :module, :constant, :type, :function]
```