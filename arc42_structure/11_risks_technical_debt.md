[<< Back](/README.md)

## Technical Debt

### Performance optimization in terms of storage.

#### Reason

In reducing code complexity and fast scaling, storage optimazation is not a top priority.

#### Reduction Efforts

- Reducing non critical redundency.

## Risks

### Vendor lock at cloud services

#### Reason 

In Reducing complexity and cutting cost at the team, only one cloud provider is chosen. Self hosting is no option. Only one expert at cloud computing is needed to build our product.

#### Mitigation Efforts

- Keep a clear structure of our services. 
- Do stuff in house rather than using all services of the cloud provider.

### Version issues

#### Reason

Complex versioning arises in the microservice architecture. All services need to stay compatible with eachother and on many differnt devices. 

#### Mitigation Efforts

- Hold on to versioning conventions tightly.
- Keep track of versioning centralized.