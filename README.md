# SailPoint IdentityIQ – Custom Java Connector

This project demonstrates how to build a custom Java connector for SailPoint IdentityIQ (IIS). The connector simulates integration with a fictional HR system using a REST API or local data file.

## 💡 Use Case

Create a lightweight connector to:

- Aggregate identities from an external source
- Map attributes to SailPoint schema
- Simulate provisioning (create/update/delete)
- Provide logging and error handling for visibility

## 📁 Project Structure

```text
sailpoint-custom-connector/
├── connector/
│   ├── src/com/example/sailpoint/MyConnector.java   # Connector implementation
│   └── resources/
│       ├── connector-config.xml                     # Schema, attributes, connection settings
│       └── application-init.xml                     # SailPoint init file
├── test-harness/                                    # Dummy system simulation
│   └── DummySystem.java
├── docs/                                            # Diagrams and usage notes
├── build.gradle                                     # Build system (Gradle or Maven)
└── README.md
```

## 🛠 Technologies

- Java 8+
- SailPoint IdentityIQ SDK (interface stubs included)
- (Optional) Local SailPoint dev instance in Tomcat
- Gradle (or Maven)

## 🔐 IAM Concepts Demonstrated

- Account aggregation
- Identity attribute mapping
- Custom connector lifecycle
- Schema provisioning plan structure
- Simulated entitlement handling

## 📚 Documentation

- docs/walkthrough.md
- docs/connector-architecture.png
