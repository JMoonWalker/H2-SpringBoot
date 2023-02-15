# Getting Started

### Reference Documentation

###### if you want to use an in memory database so, use "jdbc:h2:mem", "mem" means inMemory

spring.datasource.url=jdbc:h2:***mem***:testdb


###### if you want to use a file(not in memory database), so use "jdbc:h2:file" instead of "mem", and just name the file and do not create any file
the H2 will create the files automatically.

spring.datasource.url=jdbc:h2:***file***:C:/projects/samples/h2/src/main/resources/data/employees;AUTO_SERVER=TRUE

<ul>
  <li>First item</li>
  <li>Second item</li>
  <li>Third item
    <ul>
      <li>Indented item</li>
      <li>Indented item</li>
    </ul>
  </li>
  <li>Fourth item</li>
</ul> 