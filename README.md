# ECU Tuning Projects

This directory contains the following projects:

1. **ecu-core**: Core ECU communication library
   - Basic ECU communication
   - Safety features
   - Cross-platform support

2. **ecu-efficiency**: Engine efficiency calculations
   - VE calculations
   - Air flow modeling
   - Temperature compensation

3. **ecu-scaling**: Map scaling and optimization
   - Map scaling algorithms
   - Interpolation methods
   - Table optimization

4. **ecu-maui**: Cross-platform MAUI application
   - Real-time monitoring
   - Map editing interface
   - Data logging

## Building the Projects

### C++ Projects (ecu-core, ecu-efficiency, ecu-scaling)
```bash
cd <project-directory>
mkdir build && cd build
cmake ..
cmake --build .
```

### MAUI Project (ecu-maui)
```bash
cd ecu-maui
dotnet build
```

## Uploading to GitHub
1. Create repositories on GitHub
2. Initialize git in each project directory
3. Add remote and push:
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git remote add origin https://github.com/yourusername/repo-name.git
   git push -u origin main
   ```
