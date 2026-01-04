# Population Genetics Simulator

An interactive web-based tool for visualizing and understanding fundamental concepts in population genetics, including allele frequency changes, natural selection, genetic drift, and mutation.

![Population Genetics Simulator](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

## Overview

This simulator provides an educational platform for students, educators, and anyone interested in understanding how genetic variation changes over time in populations. It demonstrates key principles from evolutionary biology and population genetics through interactive visualizations.

![Screenshot_4-1-2026_82359_127 0 0 1](https://github.com/user-attachments/assets/7afe5a7c-fdc2-4eaa-8b8c-f48588fc00aa)

## Features

### Interactive Parameters
- **Population Size**: Adjust from 100 to 5,000 individuals
- **Initial Allele Frequency**: Set the starting frequency of allele A (0.0 to 1.0)
- **Selection Coefficient**: Apply selective pressure (-0.5 to +0.5)
  - Positive values favor the AA genotype
  - Negative values favor the aa genotype
- **Mutation Rate**: Control spontaneous allele changes (0 to 0.01)
- **Generation Steps**: Simulate multiple generations at once

### Real-Time Visualizations
- **Allele Frequency Chart**: Track changes in allele A and allele a frequencies over generations
- **Genotype Distribution**: View the proportion of AA, Aa, and aa genotypes
- **Population Display**: Visual representation of up to 1,000 individuals colored by genotype
- **Live Statistics**: Current generation, allele frequencies, and heterozygosity

### Simulation Controls
- **Next Generation**: Step through one generation at a time
- **Auto Run**: Automatically simulate 10 generations
- **Reset**: Return to initial conditions

## Educational Applications

This simulator helps demonstrate:

- **Hardy-Weinberg Equilibrium**: With no selection or mutation, allele frequencies remain constant
- **Natural Selection**: How beneficial or harmful alleles change in frequency over time
- **Genetic Drift**: Random fluctuations in allele frequencies, especially in small populations
- **Mutation-Selection Balance**: The equilibrium between new mutations and selection
- **Heterozygosity**: Changes in genetic diversity over time

## Getting Started

### Installation

No installation required! This is a standalone HTML file that runs entirely in your browser.

1. Clone the repository:
```bash
git clone https://github.com/yourusername/population-genetics-simulator.git
```

2. Open the HTML file in any modern web browser:
```bash
cd population-genetics-simulator
open index.html
```

Or simply download the HTML file and double-click to open it.

### Usage

1. **Set Initial Conditions**: Use the sliders to configure your starting population parameters
2. **Run Simulation**: Click "Next Generation" to simulate step-by-step, or "Auto Run" for continuous simulation
3. **Observe Results**: Watch the charts and statistics update in real-time
4. **Experiment**: Try different scenarios to see how selection, mutation, and drift interact

## Example Scenarios

### Scenario 1: Hardy-Weinberg Equilibrium
- Population: 1000
- Initial Allele A Frequency: 0.5
- Selection: 0.0
- Mutation: 0.0

Result: Frequencies remain stable (with minor drift)

### Scenario 2: Strong Positive Selection
- Population: 1000
- Initial Allele A Frequency: 0.1
- Selection: +0.3
- Mutation: 0.001

Result: Allele A increases rapidly in frequency

### Scenario 3: Genetic Drift in Small Populations
- Population: 100
- Initial Allele A Frequency: 0.5
- Selection: 0.0
- Mutation: 0.0

Result: Large random fluctuations, possible fixation or loss

### Scenario 4: Mutation-Selection Balance
- Population: 1000
- Initial Allele A Frequency: 0.9
- Selection: -0.1
- Mutation: 0.005

Result: Equilibrium between mutation introducing A and selection removing it

## Technical Details

### Simulation Model

The simulator uses a Wright-Fisher model with the following features:

- **Fitness-based reproduction**: Individuals reproduce proportionally to their relative fitness
- **Random mating**: Alleles are randomly combined to form offspring
- **Mutation**: Each allele can mutate at the specified rate
- **Non-overlapping generations**: Complete population replacement each generation

### Genotype Fitness Values

Given a selection coefficient `s`:
- AA fitness: 1 + s
- Aa fitness: 1 + s/2
- aa fitness: 1

## Browser Compatibility

Works on all modern browsers:
- Chrome/Edge 90+
- Firefox 88+
- Safari 14+
- Opera 76+

## Educational Resources

To learn more about population genetics:

- [Khan Academy - Population Genetics](https://www.khanacademy.org/science/ap-biology/natural-selection/population-genetics)
- [Nature Education - Population Genetics](https://www.nature.com/scitable/topic/population-genetics-14/)
- [Evolution 101 - Berkeley](https://evolution.berkeley.edu/)

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request. Some ideas for enhancements:

- Add migration between populations
- Implement multiple loci
- Add environmental fluctuations
- Include dominance relationships beyond simple dominance
- Export data as CSV for further analysis

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

Created as an educational tool for teaching population genetics concepts. Inspired by classic population genetics simulations and designed to be accessible to students at all levels.

## Contact

Om Gedam

GitHub: @itsomg134

Email: omgedam123098@gmail.com

Twitter (X): @omgedam

LinkedIn: Om Gedam

Portfolio: https://ogworks.lovable.app
