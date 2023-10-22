# Temperature Converter

A cli to convert temperatures between kelvin, Celsius and Fahrenheit

* **Install**

```
cargo install tcv
```

* **Usage**
```
$ tcv --help
Usage: tcv --temperature <TEMPERATURE> <MODE>

Arguments:
  <MODE>  The mode for conversion [possible values: k2c, c2k, f2c, c2f, f2k, k2f]

Options:
  -t, --temperature <TEMPERATURE>  Input temperature to convert
  -h, --help                       Print help information
  -V, --version                    Print version information
```

* **Kelvin to Celsius conversion**

```
$ tcv -t 0 k2c
-273.15
```

* **Fahrenheit to Celsius conversion**

```
$ tcv -t 80 f2c
26.666666666666668
```