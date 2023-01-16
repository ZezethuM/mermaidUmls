```mermaid

	classDiagram
    
	class ICar
	<<interface>> ICar
	ICar : +Accelarate()
	ICar: +Refuel() 

	ICar <|-- ElectricCar : 
	ICar <|-- PetrolCar : 
	ElectricCar : +Accelarate()
	ElectricCar: +Refuel()

	PetrolCar : +Accelarate()
	PetrolCar: +Refuel()
```


> Written with [StackEdit](https://stackedit.io/).