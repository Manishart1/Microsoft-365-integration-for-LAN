# Microsoft 365 Cloud Drive Integration for LAN Access

## Project Overview
This project demonstrates how to transform Microsoft 365 SharePoint/OneDrive into a LAN-style mapped drive, enabling seamless daily access to shared office data. It eliminates the need for temporary links and provides a backend cloud storage server experience for teams.

## Process / Implementation Steps

### 1. Setup Microsoft 365 Environment
- Create a SharePoint Document Library for team storage.
- Configure permissions and access rights for all users.

### 2. OneDrive Sync Client
- Install and configure OneDrive sync on each workstation.
- Sync the SharePoint library locally so it appears as a folder.

### 3. Persistent Drive Mapping
- Use `net use` or PowerShell scripts to map the synced folder as a drive letter.
- Configure auto-reconnect on login for persistence.

### 4. Data Migration
- Upload large datasets (e.g., 100GB) from local servers to SharePoint.
- Ensure versioning and backup policies are enabled.

### 5. Testing & Validation
- Verify team-wide access.
- Test reliability across multiple devices and sessions.

## Key Points
- **Cloud-first architecture**: Replaces traditional LAN file servers with Microsoft 365 Business Standard.
- **Persistent access**: Mapped drive behaves like a local server.
- **Scalability**: Supports large datasets and multiple users using a single Microsoft 365 Business Standard license.
- **Security**: Leverages Microsoft 365 authentication and permissions.
- **Usability**: Simplifies daily workflows by removing link-based access.

## Outcomes
- Team members can access shared files directly from a mapped drive.
- Reduced dependency on local servers.
- Improved reliability and collaboration.
- Demonstrates practical use of Microsoft 365 for small-to-medium businesses.
