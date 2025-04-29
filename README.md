# vapor-pressure-chart

# Vapor Pressure Chart Generator (Cox-style)

This repository provides R code and sample data for generating vapor pressure plots of common solvents using Cox-style charts.

## Features

- Antoine equation–based vapor pressure calculations
- Unit conversion: mmHg, hPa, kPa
- 1/(T + C) axis transformation (Cox correction)
- Publication-quality plotting (colors and B/W friendly)
- Minimal dependencies (base R + `colorspace`)

## Usage

1. Clone or download this repository.
2. Open `vapor_pressure_plot.R` in R or RStudio.
3. Modify the user settings at the top of the script.
4. Run the script to preview or save PNG graphs.

## Files

- `vapor_pressure_plot.R` – The main plotting script.
- `20250329_compound_set.csv` – Sample compound data including Antoine constants.
- `LICENSE` – License file (CC BY 4.0).

## Author

Created by [@chemica_tan](https://x.com/chemica_tan),  
a.k.a. けみかたん(化学/化学工学/生物), 乃物けみか.

## License

Distributed under [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).  
You are free to use, modify, and distribute this work with proper attribution.

Love and attribution always appreciated.

## 作者
けみかたん([@chemica_tan](https://x.com/chemica_tan)）によって作成されました。  
このコードは教育・研究用途での使用や再配布が自由にできます（CC BY 4.0）。  
ご活用の際はクレジット表記を添えていただけると嬉しいです。
