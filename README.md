hex-ddd
=======

Supporting Domain Driven Design and Hexagonal Architectures in Ruby.

Vision
======
The intent of this repository is to support building maintainable ruby applications using concepts from Domain Driven Design and Hexagonal Rails.

The ideas expressed here are meant to set an initial direction for this effort while also welcoming community involvement.

Principles
==========
* A mechanism to support *Rails* applications is important as are *Rack*, *Sinatra* and other ruby applications.
* Rails specific support should be added in seperate gems.
* It should be possible to adopt concepts and gems in an incremental manner allowing individual adoption to follow pain.
* Support should be provided for the migration of *traditional* rails applications without requiring rewriting from scratch.
* Usage of these patterns should be as simple as possible. For example something like ```include DDD::ValueObject``` should suffice to have the behavior of a *ValueObject*.




