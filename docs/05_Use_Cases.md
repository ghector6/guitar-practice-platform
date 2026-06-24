# Use Cases

## UC-001: Create Study Plan

### Description

Create a structured study plan for a student or self-managed musician.

### Actors

* Teacher
* Self-Managed Musician

### Preconditions

* A user exists.
* Exercises, pieces, and sections are available.

### Main Flow

1. Create a study plan.
2. Define the duration.
3. Add exercises.
4. Add repertoire sections.
5. Define goals.
6. Save the study plan.

### Result

A study plan becomes available for practice.

---

## UC-002: Assign Technical Exercises

### Description

Assign technical material to a study plan.

### Actors

* Teacher
* Self-Managed Musician

### Preconditions

* A study plan exists.
* Exercises exist.

### Main Flow

1. Select an exercise.
2. Select a variant.
3. Define target BPM.
4. Define difficulty.
5. Add the exercise to the study plan.

### Result

Technical material is assigned.

---

## UC-003: Assign Repertoire Sections

### Description

Assign sections of musical works.

### Actors

* Teacher
* Self-Managed Musician

### Preconditions

* Pieces and sections exist.

### Main Flow

1. Select a piece.
2. Select one or more sections.
3. Define target BPM.
4. Define target quality.
5. Save.

### Result

Repertoire material becomes part of the study plan.

---

## UC-004: Define Goals

### Description

Define measurable objectives.

### Actors

* Teacher
* Self-Managed Musician

### Preconditions

* A study plan exists.

### Main Flow

1. Select goal type.
2. Define target values.
3. Define deadline.
4. Save.

### Result

Goals are associated with the study plan.

---

## UC-005: Register Practice Session

### Description

Record a practice session.

### Actors

* Student
* Self-Managed Musician

### Preconditions

* User exists.

### Main Flow

1. Start a session.
2. Select session type.
3. Register exercises.
4. Register repertoire sections.
5. Record repetitions.
6. Record errors.
7. Record subjective score.
8. Finish session.

### Result

Practice data is stored.

---

## UC-006: Register Technical Practice

### Description

Record technical exercise performance.

### Actors

* Student
* Self-Managed Musician

### Preconditions

* Session exists.

### Main Flow

1. Select exercise.
2. Select variant.
3. Record BPM.
4. Record repetitions.
5. Record errors.
6. Record subjective score.
7. Save.

### Result

Technical practice history is preserved.

---

## UC-007: Register Repertoire Practice

### Description

Record repertoire work.

### Actors

* Student
* Self-Managed Musician

### Preconditions

* Session exists.

### Main Flow

1. Select piece.
2. Select section.
3. Record BPM.
4. Record repetitions.
5. Record errors.
6. Record subjective score.
7. Save.

### Result

Repertoire history is preserved.

---

## UC-008: Review Progress

### Description

Analyze historical performance.

### Actors

* Student
* Teacher
* Self-Managed Musician

### Preconditions

* Practice records exist.

### Main Flow

1. Select time range.
2. View practice metrics.
3. Analyze trends.

### Result

Historical insights are available.

---

## UC-009: Monitor Student Progress

### Description

Evaluate a student's development.

### Actors

* Teacher

### Preconditions

* Students and practice records exist.

### Main Flow

1. Select a student.
2. Review completed sessions.
3. Review quality metrics.
4. Review tempo progression.
5. Identify bottlenecks.

### Result

The teacher gains visibility into student performance.

---

## UC-010: Evaluate Goal Achievement

### Description

Determine whether goals have been achieved.

### Actors

* Teacher
* Student
* Self-Managed Musician

### Preconditions

* Goals exist.
* Practice records exist.

### Main Flow

1. Select a goal.
2. Compare historical data with target values.
3. Determine completion status.

### Result

Goal status is updated.

---

## UC-011: Analyze Practice Quality

### Description

Evaluate the effectiveness of practice.

### Actors

* Student
* Teacher
* Self-Managed Musician

### Preconditions

* Practice records exist.

### Main Flow

1. Review quality metrics.
2. Review tempo progression.
3. Review consistency.
4. Identify weaknesses.

### Result

Practice quality insights are generated.

---

## UC-012: Associate Technical Problems with Exercises

### Description

Link repertoire difficulties with technical exercises.

### Actors

* Teacher
* Self-Managed Musician

### Preconditions

* Sections and exercises exist.

### Main Flow

1. Select a section.
2. Identify technical problems.
3. Select exercises that address those problems.
4. Save relationships.

### Result

Repertoire and technical work become integrated.

---

## UC-013: Create Custom Variants

### Description

Define personalized study approaches.

### Actors

* Teacher
* Self-Managed Musician

### Preconditions

* Exercises or sections exist.

### Main Flow

1. Define the variant.
2. Specify the rhythmic or technical configuration.
3. Save.

### Result

Custom variants become available for future use.

