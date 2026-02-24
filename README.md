🌟 AIR: Always Inspection Ready

Project Focus:

  Enterprise Asset Management (EAM), Clinical Compliance, and Operational Quality Assurance (QA/QI) Automation System.

Purpose:

  Developed as a comprehensive Claris/FileMaker application to operationalize and automate hospital operations, compliance, and quality control, applying EMR-level security and scheduling features to equipment, personnel, and documentation.

🎯 Key Design & Architectural Highlights

Role-Based Permissions & Security:

  Users are categorized by Specialty, which dictates granular, role-based permissions. User assignment to Departments is managed via unique Keys that define permission levels per assignment, ensuring strict data access control.

Flexible Resource Scheduling:

  Resources (e.g., instruments, equipment) are joined to multiple departments via a Link entity. This prevents scheduling conflicts and allows Tasks (like PMs or calibrations) to be scheduled independently by specialty without impacting other user groups.

Procedural Dependency Modeling:

  A central Procedure hub defines either required documentation or services (like a lab test). The join of Procedure to a Resource is defined as a Method, allowing tasks to be assigned to a specific Method. This structure enables method statuses to flow back to both resources and procedures, ensuring audit trails and compliance tracking.

Data Model Proof:

  The relational structure and data flows are documented in the **[AIR Gold Copy](https://kirk-allen-ryan.github.io/AIR/AIR.GC_ddr/AIR.GC_n.html)** included in this repository.

System Demo:

  See the multi-user scheduling, permission structure, and automated task assignments in action. Watch the Full System Demo Video on YouTube
