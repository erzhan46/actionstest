# Environment promotion PoC

Options to consider:
- Current flat folder sctructure
- Environments as separate repositories

## Flat folder structure
Workflow(s) for each environment will have scope limited by paths:
- Internal/ProvingGround/EastUS/01 
- Internal/Learning/EastUS/01 
- Internal/Management/EastUS/01 
- Consumer/Engineering/EastUS/01 
- Consumer/Platform/EastUS/01 
- Consumer/Management/EastUS/01

Each clsuter for each environment will have separate subdirectory.

Promotion between environments - copying / merging files using OS tools.

Approval - pull requests / environment approvals
