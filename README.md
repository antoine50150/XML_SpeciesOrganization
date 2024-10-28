# Observations of Species

This project is an XML-based data representation of various species observations in different locations. The data includes details about the species, their habitat locations, and the number of individuals observed over different years.

## Project Structure

The project contains an XML file structured as follows:

- **Lieux**: Contains geographical locations where observations were made.
- **Especes**: Lists different species along with their descriptions.
- **Observations**: Records the number of individuals observed for each species at specific locations and years.

### XML Structure

```xml
<Observations>
    <Lieux>
        ...
    </Lieux>
    
    <Especes>
        ...
    </Especes>
    
    <Observations>
        ...
    </Observations>
</Observations>
