Week 1-2
```mermaid
classDiagram
      Project <|-- Requirements
      Project <|-- DevEnvironment
      Project <|-- RuntimeEnvironment
      Project : +PM()
      Project : +Customer(BroClements)
      class Requirements{
          +String Lead()
          +String TeamMember(Joshua Ellis)

      }
      class DevEnvironment{
          +String Lead()
          +String TeamMember()
          +String TeamMember()
      }
      class RuntimeEnvironment{
          +String Lead()
          +String TeamMember()
          +String TeamMember()
      }
```
Rest of the Semester
```mermaid
classDiagram
      Project <|-- FrontEnd
      Project <|-- BackEnd
      Project <|-- Database
      Project : +PM()
      Project : +Customer(BroClements)
      class FrontEnd{
          +String Lead()
          +String TeamMember(Joshua Ellis)

      }
      class BackEnd{
          +String Lead()
          +String TeamMember()

      }
      class Database{
          +String Lead()
          +String TeamMember(Abby Joseph)
      }
```
