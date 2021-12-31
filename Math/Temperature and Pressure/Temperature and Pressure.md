# Temperature and Pressure

Informational Requirements: 

- "T" for temperature
- "V" for volume
- "°C" for degrees Celsius (or Centigrade)
- "°F" for degrees Fahrenheit
- subscript "1" for a starting value
- subscript "2" for an ending value
- Kelvin constant: 273
- Rankine constant: 460
- Guage to ambient constant: 1bar or 14.7psi

## Generalized Guy-Lussac's Law

$$
\frac{P_1}{T_1}=\frac{P_2}{T_2}
$$

## Kelvin and Rankine Conversion Constants

$$
°K=°C+273
$$

$$
°R=°F+460
$$

### Kelvin and Rankine Formulae Equivalents with Algebra

$$
Bar_2 = \frac{(°C_2+273)(Bar_1+1bar)}{°C_1+273}-1bar
$$

$$
Atm_2= \frac{(°F_2+460)(Atm_1+14.7psi)}{°F_1+460}-14.7psi
$$

### Examples

> If the pressure of gas inside a scuba cylinder is 200 bar at a temperature of 30°C, what will be its pressure at 10°C?

$$
\frac{(10°C+273)(200bar+1bar)}{30°C+273}-1bar=186.73bar
$$

> If the pressure of gas inside a scuba cylinder is 3000 psi at a temperature of 90°F, what will be its pressure at 50°F?

$$
\frac{(50°F+460)(3000psi+14.7psi)}{90°F+460}-14.7atm=2780.75
$$

## Estimation

$$
1°C\approx0.6bar
$$

$$
1°F\approx5psi
$$

### Estimation Examples

> What will be the change in pressure inside a scuba cylinder, when it is taken from a surface temperature of 30°C to an underwater temperature of 10°C?

$$
(30°C-10°C)*0.6bar=12bar
$$

> What will be the change in pressure inside a scuba cylinder, when it is taken from a surface temperature of 90°F to an underwater temperature of 50°F?

$$
(90°F-50°F)*5psi=40psi
$$