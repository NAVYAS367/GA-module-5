# Assignment 5: Graph Analytics Using Neo4j

## University Course Registration System

### 1. Project Overview
This project implements a University Course Registration System using Neo4j, a graph database, and the Cypher query language. It represents students, faculty members, courses, and academic departments as nodes and their associations as relationships.

### 2. Objectives
- Create student, faculty, course, and department nodes.
- Establish relationships between nodes with appropriate directions.
- Assign properties to relationships.
- Retrieve and filter graph data using Cypher queries.
- Verify node counts, relationship types, and graph structure.

### 3. Technologies Used
- **Database:** Neo4j
- **Query Language:** Cypher
- **Environment:** Neo4j Browser / Neo4j Desktop

### 4. Graph Data Model

#### Node Labels
| Node Label | Description | Count |
|---|---|---:|
| Student | University students | 5 |
| Faculty | Faculty members | 2 |
| Course | Academic courses | 5 |
| Department | Academic departments | 2 |

#### Relationship Types
| Relationship | Direction | Description |
|---|---|---|
| ENROLLED_IN | Student → Course | Student enrolment in a course |
| TEACHES | Faculty → Course | Faculty member teaching a course |
| BELONGS_TO | Student → Department | Student's department |
| OFFERS | Department → Course | Department offering a course |

### 5. Relationship Properties
- **ENROLLED_IN**
  - `semesterEnrolled`: Semester in which the student enrolled.
  - `grade`: Grade status, set to `Not Published`.
- **TEACHES**
  - `
