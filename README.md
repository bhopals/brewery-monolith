## brewery-monolith
- A monolith Application

### Beer Works Monolith
- Beer Works - Models a Brewery
- The Beer work brewery has:
    - Beers!
    - Beer Inventory
    - Beer Orders
    - Customers

- Beer Works - Tasting Room
    - Creates ‘demand’ - Brewery needs to consume beer inventory for tasting room orders
    - Demand triggers inventory reduction
    - Inventory reduction will trigger brewing of beer
    - Brewing will create inventory

### Technology Stack
- Spring Boot / Spring Framework
- Hibernate / Spring Data JPA
- Spring MVC
- Project Lombok / Mapstruct
- Thymeleaf for UI Views
- Spring Scheduled Tasks
- Spring Events