# Module 1: Introduction to Version Control

## What is Version Control?
Version Control is a system that records changes to a file or set of files over time so that you can recall specific versions later. It is an essential tool for developers, designers, and teams who work on collaborative or long-term projects. 

Key points:
- Tracks the history of changes made to files.
- Allows users to revert to previous versions if needed.
- Facilitates collaboration by managing concurrent edits from multiple users.

---

## Benefits of Version Control Systems (VCS)
Version Control Systems provide a wide range of advantages, making them indispensable for project management and software development:

1. **History Tracking**  
   - Maintain a complete history of changes, including who made them and when.
   - Retrieve older versions or changes if needed.

2. **Collaboration**  
   - Enable multiple contributors to work on the same project simultaneously without overwriting each other’s work.

3. **Backup and Recovery**  
   - Files stored in a VCS serve as a reliable backup.
   - Easily recover previous versions in case of errors or accidental deletion.

4. **Branching and Merging**  
   - Experiment with new features in isolated environments (branches).
   - Merge changes from different branches into a stable codebase.

5. **Accountability**  
   - Changes are tied to specific users, making it clear who contributed what.

6. **Consistency Across Teams**  
   - Centralized repositories ensure everyone is working on the latest version of the project.

---

## Types of Version Control Systems: Centralized vs Distributed
Version Control Systems can be broadly classified into two categories based on their architecture:

### 1. Centralized Version Control Systems (CVCS)
- **Definition**: A single server stores all versioned files, and clients access this central repository.
- **Examples**: Subversion (SVN), Perforce.
- **Advantages**:
  - Simple to set up and use.
  - Centralized management makes it easy to maintain control over access.
- **Disadvantages**:
  - Single point of failure: If the server goes down, access to the repository is lost.
  - Limited offline capabilities.

### 2. Distributed Version Control Systems (DVCS)
- **Definition**: Every user has a complete copy of the repository, including its history, on their local machine.
- **Examples**: Git, Mercurial.
- **Advantages**:
  - Works offline: Local copies enable developers to work without a connection to the central server.
  - Faster operations: Actions like commits, diffs, and history checks are performed locally.
  - Better resilience: No single point of failure; repositories can be cloned and restored easily.
- **Disadvantages**:
  - Initial learning curve may be steeper than CVCS.
  - Larger storage requirements as each user maintains a full copy of the repository.

---

### Conclusion
Understanding the basics of Version Control, its benefits, and the differences between centralized and distributed systems provides a foundation for efficient collaboration and project management. In the next module, we will explore the most popular DVCS, Git, and learn how to use it effectively.
