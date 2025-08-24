# airbnb-clone-project
## Team Roles
- BAckend Developer:Responsible for implementing API endpoints, databse schemas, and business logic.
- Database Administrator: manaages database design, indexing, and optimizations.
Dev Ops Engineer; Handles deployment,monitoring, scaling of the backend services
- QA Engineeer: Ensures the backend functionalities are thoroughly tested and meet the quality standards


## Technology Stack
- Django
- GraphQL
- Django REST Framework
- PostgreSQL
- Celery
- Redis
- Docker
- CI/CD Pipelines

## Database Design
- Users: 1.User can have multiple props
        2.User can 
- Bookings: 1. Number of props booked 
- Properties: 1. Houses listed by user
             2. Each property has its own review
             3.
- Payments: 1. Payments are made based on bookings
- Reviews: 1.Review are made on properties
          2. User can reply to review or delete it


## Feature Breadown
- API Documentation
- User Authentication
- Property Management
- Bookingg System
- Payment Processing
- Review System
- Database Optimizations

## API Security
- Authentication: verifying the users to see if theyre real people and not bot and also to check if the property listed belongs to them or they have the access they're claiming to have.
- Otp Verification: OTP will be requested everytime a user logs into an account on a new device
- Rate Limitting: controlling the rate at which a server receives a request which helpa prevent resourse exhaustion and abuse
- Authorization: granting official approval to users to access a resource or perform a particuular action, and also definin the specific rights of a user.

## CI/CD Pipeline
- Continuous INtegration(CI): Merging codes into a shared repository for it to be automatically built and tested.
- Continuous Delivery/Deployment(CD): After vode passes test, its automatically prepared for release.
- The Pipeline is the automatic workflow the code passes through before reaching users 



