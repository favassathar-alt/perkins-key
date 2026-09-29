# 🔑 Perkins Key

Advanced refrigerant quantity calculator for HVAC systems. Calculate circuit mass requirements based on physical configurations.

## Features

✅ **Real-time Calculations** - Instant results as you adjust parameters
✅ **Support for Multiple Refrigerants** - R410A and R32
✅ **Flexible Fin Types** - Louvre, Sine Wave, and Corrugated options
✅ **Circuit Configuration** - Both 2x2 and 2x1 circuit types
✅ **Validation & Warnings** - Smart alerts for configuration constraints
✅ **Beautiful UI** - Modern dark theme with responsive design
✅ **No Source Code Exposure** - Share single HTML file, calculations hidden

## How to Use

1. **Select Refrigerant Type** - Choose between R410A or R32
2. **Choose Fin Type** - Select your heat exchanger fin design
3. **Enter Dimensions** - Input finned length and span length in mm
4. **Set Tubes Per Row** - Number of tubes in your configuration
5. **View Results** - Calculated mass appears instantly for valid configurations

## Technical Details

### Supported Refrigerants
- **R410A**: Specific Length = 130g
- **R32**: Specific Length = 116g

### Circuit Types
- **2x2 Circuit**: Always available for all configurations
- **2x1 Circuit**: Only available when tubes per row is an even number

### Calculations
- **2x2 Circuit**: Uses span divisor (2.0 for R410A, 4.0 for R32) and fin-type multiplier
- **2x1 Circuit**: Uses mass multiplier (1.15 for R410A, 1.05 for R32)

## Access Online

🔗 **Live Calculator**: https://favassathar-alt.github.io/perkins-key/

Simply share this link with your team - no installation or coding knowledge required!

## How It Works

The calculator is a single HTML file containing:
- All calculation logic (hidden from users)
- Beautiful responsive UI built with Tailwind CSS
- Real-time computation without server calls
- No dependencies on external backends

Users can only see inputs and outputs - the actual formulas remain private.

---

Created with ❤️ for HVAC professionals
