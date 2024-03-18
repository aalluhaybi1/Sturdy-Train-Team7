# Welcome to Sturdy-Train-Team7
# StudentSmartRentals
![una-rent](https://github.com/aalluhaybi1/Sturdy-Train-Team7/assets/156353463/81b5a140-1d1d-40df-8666-54151fc4ede7)

# Product Overview

- The Rental & Services Management System project, driven by the founder's experiences, aims to make the moving-in process easier for local and international students.
- It addresses gaps in the rental platform market, focusing on apartment rentals and related services tailored for students at Indiana University of Bloomington. 
- The system features extensive property listings, including details like proximity to essential amenities, thus centralizing information and reducing the need to visit multiple platforms.
- It also offers tools such as multimedia content, map views, and user reviews to aid in decision-making, and simplifies the access to services like transportation and utilities setup.
- By integrating messaging and chat, it creates a community space that enhances the experience for international students during a pivotal life transition.

## Introduction

We're going to build an API for an apartment management company. Create the
following database structure. You will have three models (and their
corresponding tables), `Apartment`, `Tenant` and `Lease`, with the following
relationships:

- A tenant has many apartments and has many leases
- An apartment has many tenants and has many leases
- A lease belongs to an apartment and belongs to a tenant

The models should have the following attributes (along with any attributes
needed to create the relationships defined above):

- Apartment
  - number
- Tenant
  - name (must be present)
  - age (must be >= 18)
- Lease
  - rent

Make sure to define validations for your models so that no bad data can be saved
to the database.
