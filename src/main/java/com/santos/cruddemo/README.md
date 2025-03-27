Day 26: Advanced JPA Mappings

Today, I learned about JPA/Hibernate advanced mappings, focusing on @OneToOne relationships.

1) @OneToOne Mapping:
- Learned how to create 1:1 relationships between entities.
- Set up the database schema for bidirectional linking.
- Configured cascading in a Spring Boot project.

-->Unidirectional @OneToOne Relationship:
- Established unidirectional one-to-one relationships, where only one side (e.g., `Instructor`) knows about the other (`InstructorDetail`).
- Set up the foreign key in the `Instructor` table using `@JoinColumn` to reference `InstructorDetail`.
