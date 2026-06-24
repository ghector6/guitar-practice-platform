# Business Rules

## Session Rules

### BR-001: Session Types

A practice session may be one of the following types:

* Technique
* Repertoire
* Mixed

---

### BR-002: Session Duration

The recommended duration of a practice session is between 20 and 50 minutes.

Sessions outside this range are allowed but should be flagged for analytical purposes.

---

### BR-003: Session Content

A session may contain:

* Multiple exercises.
* Multiple repertoire sections.

There is no upper limit on the number of items contained within a session.

---

### BR-004: Multiple Sessions Per Day

Users may perform multiple sessions per day.

Rest periods between sessions are recommended but are not enforced by the system.

---

## Study Plan Rules

### BR-005: Study Plan Ownership

A study plan may be created by:

* A teacher.
* A self-managed musician.

---

### BR-006: Study Plan Duration

Study plans may be:

* Weekly.
* Monthly.
* Semester-based.

---

### BR-007: Study Plan Content

A study plan may contain:

* Exercises.
* Variants.
* Repertoire sections.
* Goals.

---

## Exercise Rules

### BR-008: Exercise Sources

Exercises may originate from different methods, authors, or educational materials.

The platform does not impose restrictions on exercise sources.

---

### BR-009: Exercise Difficulty

Exercise difficulty is subjective.

Difficulty values are defined by the teacher and depend on context.

Difficulty is not an intrinsic property of an exercise.

Difficulty may depend on:

* Variant.
* Target BPM.
* Student level.
* Teacher criteria.

---

### BR-010: Exercise Relationships

An exercise may develop one or more technique elements.

Relationships between exercises and technique elements are many-to-many.

---

## Variant Rules

### BR-011: Variant Scope

Variants may be applied to:

* Exercises.
* Repertoire sections.

---

### BR-012: Variant Types

Variants may represent:

* Rhythmic patterns.
* Custom rhythmic combinations.
* Teacher-defined configurations.
* Personalized study approaches.

---

### BR-013: Variant Catalog

There is no universal catalog of variants.

Users are allowed to define custom variants.

---

## Piece and Section Rules

### BR-014: Piece Composition

A piece consists of one or more sections.

---

### BR-015: Section Definition

A section represents a range of measures belonging to a piece.

Sections are used to isolate and solve technical problems.

---

### BR-016: Section Relationships

A section may require multiple technique elements.

Relationships between sections and technique elements are many-to-many.

---

### BR-017: Repertoire and Technique Integration

Sections may be associated with technical exercises intended to address the underlying difficulty.

These relationships are informational and do not imply exclusivity.

---

## Goal Rules

### BR-018: Goal Types

Goals may be:

* Weekly.
* Monthly.
* Semester-based.

---

### BR-019: Goal Scope

Goals may target:

* Exercises.
* Repertoire sections.
* Complete pieces.
* Concert programs.
* Exams.
* Competitions.
* Auditions.

---

### BR-020: Goal Metrics

Goals may define:

* Target BPM.
* Minimum quality percentage.
* Completion percentage.
* Total repertoire duration.

---

## Teacher Rules

### BR-021: Material Assignment

Teachers may assign:

* Exercises.
* Variants.
* Pieces.
* Sections.
* Goals.

---

### BR-022: Difficulty Assignment

Difficulty levels are defined by teachers.

The platform does not enforce a universal difficulty scale.

---

## Student Rules

### BR-023: Practice Registration

Students are responsible for recording practice sessions.

---

### BR-024: Self-Managed Users

A self-managed musician may simultaneously act as:

* Teacher.
* Student.

---

## Institution Rules

### BR-025: Institutional Structure

Institutions may contain:

* Multiple teachers.
* Multiple students.

---

### BR-026: Teacher-Student Relationships

A teacher may supervise multiple students.

A student may belong to one or more teachers depending on the institution's structure.

---

## Analytics Rules

### BR-027: Practice Quality

Quality is derived from objective and subjective metrics.

Quality calculations may consider:

* Errors.
* Repetitions.
* Subjective score.

The calculation formula may evolve over time.

---

### BR-028: Tempo Progression

Tempo increases should occur only when the quality threshold defined by the teacher has been achieved.

---

### BR-029: Historical Preservation

Practice records are immutable.

Historical records must never be modified after being created.

Corrections should generate new records rather than overwrite previous data.

---

### BR-030: Extensibility

The platform must support future expansion without requiring major redesigns of the domain model.

Examples include:

* Institutions.
* Competitions.
* Recommendation systems.
* Machine learning models.
* Multi-user environments.
* Mobile applications.

