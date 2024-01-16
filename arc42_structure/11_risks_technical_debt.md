[<< Back](/README.md)

## Technical Debt

### Performance Optimization

#### Reason

In reducing code complexity and fast scaling, storage optimization is not a top priority.

#### Reduction efforts

- Reducing non critical redundancy.

## Risks

### Vendor Lock-in 

#### Reason 

In reducing complexity and cutting cost at the team, only one cloud provider is chosen. Self hosting is not an option. Only one expert in cloud computing is needed to build our product.

#### Mitigation efforts

- Keep a clear structure of our services. 
- Do stuff in house rather than using all services of the cloud provider.

### Version Issues

#### Reason

Complex versioning arises in the microservice architecture. All services need to stay compatible with each other and on many different devices. 

#### Mitigation Efforts

- Strict adherence to versioning conventions.
- Centralized version tracking.
