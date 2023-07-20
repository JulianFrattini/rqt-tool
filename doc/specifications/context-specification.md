# Context Specification

This document contains the context specification for the proposed tool operationalizing the **requirements quality theory** (RQT), in the following referred to as the **RQT tool**.

## Scope

The scope of the RQT tool is a command line tool (CLI) processing requirements entities and context information to predict the estimated impact on requirements-affected activities. The RQT tool itself does not include a graphical user interface (GUI) but future projects shall be able to integrate the RQT tool in an application offering a GUI.

## Objectives and Goals

The RQT tool has the following goals (formulated using the Connextra template "As a \<role> I want to \<goal> in order to \<benefit>."):

* **G1**: As a \<researcher> I want to \<be able to train an impact prediction model based on historic data> in order to \<optimize the impact prediction for a specific company context>.
* **G2**: As a \<researcher> I want to \<be able to add further quality factors, context factors, and activity attributes> in order to \<adjust the operationalization of the RQT>.
* **G3**: As a \<developer> I want to \<identify defects in natural language requirements> in order to \<remove them before the requirement is used in a subsequent activity>.
  * **G3.1**: As a \<developer> I want to \<see the estimated impact of a defect in natural language requirements> in order to \<decide whether the defect is worth removing>.
  * **G3.2**: As a \<developer> I want to \<receive a proposal for fixing the defect> in order to \<effectively remove the defect>.
* **G4**: As a \<manager> I want to \<get an overview of the estimated impact of a set of requirements> in order to \<understand the current quality of my requirements>.

The RQT tool is intended to be developed while adhering to open science principles in order to allow collaboration and community contribution. [GitHub](https://github.com/) will be used to orchestrate the collaboration and [Zenodo](https://zenodo.org/) for regularly archiving relevant increments.

## Proposed Architecture

The following visualization contains a proposed architecture for the RQT tool:

![Proposed Architecture of the RQT Tool](./../figures/gere-architecture.png)

Rather than imposing a solution before a proper requirements elicitation and specification, this UML component diagram shall indicate the scope and responsibilities of the necessary parts of the tool. The diagram is in no way binding for the actual architecture of the tool.