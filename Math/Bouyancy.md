# Buoyancy Calculations

## Buoyancy

Informational Requirements:

1. Object weight
1. Volume of water displaced by the object
1. Weight of displaced water

### Imperial

$$
Buoyancy = weightOfObject- [(cubicFeetDisplaced)(lbsPerCubicFootOfWater)]
$$

> What is the buoyancy of an object in seawater object that weighs 55 pounds and displaces 0.75 cubic feet?
> 
> $
> 55lbs > [0.75ft^3 x 64lbs] = 7lbs
> $
> 
> The object is 7lbs negatively buoyant.

> What is the buoyancy of an object in freshwater that weighs 40 pounds and displaces 0.75 cubic feet?
> 
> $
> 40lbs > [0.75ft^3 x 62.4lbs] = -6.8lbs
> $
> 
> The object is 6.8lbs positively buoyant.

#### Lift Gas Required

To calculate the gas required to lift an object:

$$
litersRequired = |[buoyancyInKg] / [lbs/lbsPercubicFootOfWater]|
$$

A better way to think about this may be to just ditch the absolute value and:

$$
ft^3required= |[negativeBuoyancyInKg] / [kg/literOfWater]|
$$

> How much air must be added to an attached lift to achieve neutral buoyancy for an object that is 10 pounds > negatively buoyant in seawater?
>
> 10lbs / 64lbsPerCubicFoot = 0.156ft^3 air
>
> The object will take 0.156ft^3 of air to lift.

#### Associated Facts

$
1ft^3 seawater = 64lbs
$

$
1ft^3 freshwater = 62.4lbs
$

### Metric

$$
Buoyancy = weightOfObject- [(litersDisplaced)(kg/literOfWater)]
$$

> What is the buoyancy of an object in seawater that weighs 20 kilograms and displaces 15 liters?
>
> $$
> 20kg - (15)(1.03) = -4.55kg
> $$
>
> The object is negative 4.55kg buoyant.

> What is the buoyancy of an object in freshwater that weighs 10kg and displaces 15L?
>
> $$
> 10kg - (15L*1.0) = 5kg
> $$
>
> The object is 5kg positively buoyant.

#### Lift Gas Required

To calculate the gas required to lift an object:

$$
litersRequired = |[buoyancyInKg] / [kg/literOfWater]|
$$

A better way to think about this may be to just ditch the absolute value and:

$$
litersRequired = |[negativeBuoyancyInKg] / [kg/literOfWater]|
$$

> How much air must be added to an attached lift bag to achieve neutral buoyancy for an object that is 4 kg negatively buoyant in seawater?
>
> $$
> \frac{4kg}{1.03kg/L} = 3.88L
> $$
>
> The object would require 3.88L of air to lift.

#### Associated Facts

$
1L seawater = 1.03kg
$

$
1ft^3 freshwater = 1.0kg
$