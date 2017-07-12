#### **[Check out creator's details](https://akshayanandraut.github.io)**

---

# Unit Converter API

---

## Convert units easily with this API. Read this documentation for detailed information.

---

### API usage : 
 
#### GET
```

https://akshayanand.herokuapp.com/api/unit/?type=type&from=from&to=to&value=value

```


---

### Parameters:

```

type   -  The type of unit (i.e. length, temperature, etc.) 
from -  Specifies the from unit.
to -  Specifies the to unit.
value -  Specifies the value to convert.

```

-----

### Output format:

#### The output response will be in JSON format. Kindly check the structure below.


##### JSON format

```json	

"data":{
	"unitType" : "unitType",
	"from" : "from",
	"fromUnit" : "fromUnit",
	"to" : "to",
	"toUnit" : "toUnit",
	"value" : value,
	"result" : result
}


```

---


##### NOTE:

_Please go through the location codes and error codes page to properly use the api call parameters avoid confusion._


---


## Type Codes

**_Type code_** | **_Type_**

**len** | Length
**temp** | Temperature
**area** | Area
**vol** | Volume
**weight** | Weight
**time** | Time


---


## Unit Codes

### LENGTH

**_Unit code_** | **_Unit_**

**mts** | Meters
**kilomts** | Kilometers
**cmts** | Centimeters
**millimts** | Millimeters
**micromts** | Micrometers
**nanomts** | Nanometers
**mile** | Miles
**yard** | Yards
**foot** | Foot
**inch** | Inches
**lightyear** | Light Year


### TEMPERATURE

**_Unit code_** | **_Unit_**

**celsius** | Celsius
**kelvin** | Kelvin
**fahrenheit** | Fahrenheit


### AREA

**_Unit code_** | **_Unit_**

**sqmts** | Square Meters
**sqkmts** | Square Kilometers
**sqcmts** | Square Centimeters
**sqmmts** | Square Millimeters
**sqmicromts** | Square Micrometers
**hectare** | Hectares
**sqmile** | Square Mile
**sqyard** | Square Yards
**sqft** | Square Feet
**sqinch** | Square Inches
**acre** | Acres

### VOLUME

**_Unit code_** | **_Unit_**

**cumts** | Cubic Meter
**cukmts** | Cubic Kilometer
**cucmts** | Cubic Centimeter
**cummts** | Cubic Millimeter
**lts** | Liter
**mlts** | Millimeter
**usgallon** | US Gallon
**usquart** | US Quart
**uspint** | US Pint
**uscup** | US Cup
**usfluidounce** | US Fluid Ounce
**ustablebspoon** | US Table Spoon
**usteaspoon** | US Tea Spoon
**impgallon** | Imperial Gallon
**impquart** | Imperial Quart
**imppint** | Imperial Pint
**impfluidounce** | Imperial Fluid Ounce
**imptablespoon** | Imperial Table Spoon
**impteaspoon** | Imperial Tea Spoon
**cumile** | Cubic Mile
**cuyard** | cubic Yard
**cufoot** | Cubic Foot
**cuinch** | Cubic Inch


### WEIGHT

**_Unit code_** | **_Unit_**

**kgms** | Kilogram
**gms** | Gram
**mgms** | Milligram
**metricton** | Metric Ton
**longton** | Long Ton
**shortton** | Short Ton
**pound** | Pound
**ounce** | Ounce
**carrat** | Carrat
**atomicmass** | Atomic Mass Unit


### TIME

**_Unit code_** | **_Unit_**

**sec** | Second
**milisec** | Millisecond
**microsec** | Microsecond
**nanosec** | Nanosecond
**picosec** | Picosecond
**min** | Minute
**hour** | Hour
**day** | Day
**week** | Week
**month** | Month
**year** | Year


 -----	
 
## Error Codes

 **_ERROR NO._** | **_ERROR_** | **_DESCRIPTION_**
-------------- | -------------- | ----------------
	**001**    | *ERROR001* | This error occues if there is a problem with the input data and/or parameters specified.
    
    
-----

[Visit the creator's site...](https://akshayanandraut.github.io)