# TDD Adventure - Pair Programming Demo

This project demonstrates building a simple text adventure in Java using Test-Driven Development (TDD) and pair programming techniques.

## Technologies

* Java 11
* JUnit 5
* Mockito
* AssertJ

## Setup Instructions

1. **Prerequisites:**
   * Java Development Kit (JDK) 11
   * IntelliJ IDEA Community Edition 2023.3.5 (with New UI disabled)

2. **Clone:**
   `git clone https://github.com/kirklund/tdd-adventure`

3. **Open In IntelliJ IDEA:**
   Project should import dependencies automatically.

4. **Import Project Code Style:**
   * Navigate to **File** > **Settings** (or **IntelliJ IDEA** > **Preferences** on macOS) > **Editor** > **Code Style**.
   * Click on the gear icon next to **Scheme**, select **Import Scheme**, then **IntelliJ IDEA code style XML**.
   * Choose the `intellij-reusable-java-style.xml` file from the project directory and click **OK**.

5. **Import Project Inspections Profile:**
   * Go to **File** > **Settings** (or **IntelliJ IDEA** > **Preferences** on macOS) > **Editor** > **Inspections**.
   * Click on the gear icon next to **Profile**, select **Import Profile**, then navigate to and select the `intellij-reusable-java-inspections.xml` file from the project directory.
   * Click **OK** to apply the inspections profile.

6. **Initial Starter Test:**
   `TddAdventureTest.java` outlines a basic failing test to begin TDD flow.

## TDD and Collaboration

This project emphasizes a TDD approach. Our collaborative goal is to implement and iteratively design a text adventure.

## APIs

* JUnit: https://junit.org/junit5/docs/5.9.0/api/index.html
* Mockito: https://javadoc.io/doc/org.mockito/mockito-core/latest/index.html
* AssertJ: https://www.javadoc.io/doc/org.assertj/assertj-core/latest/index.html
