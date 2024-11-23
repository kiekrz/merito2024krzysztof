# Merito2024Krzysztof
## Laboratoria z GITa

* Ćwiczenia:
1. Creational.AbstractFactory:
	- Provide an interface for creating families of related or dependent objects without specifying their concrete classes.
	- Usage: Report Engine & conctere Report Factories:
		- We know that any report have shared engine (data/footer etc), but they are completely different in view (Factories):
		- PdfReports, share dependencies among report family, `ConcreteFacotry1`,
		- XlsReports, share dependencies among report family, `ConcreteFacotry2`,
		- PlainReports, share dependencies among report family, `ConcreteFacotry3`.
![alt text](https://github.com/gwasylow/dotnet-design-patterns/blob/master/Images/dp-abstract-factory.PNG)

