This repo will serve as the documentation and version controlling DBD's integrations with Intuit Quickbooks IES system.

This integration works by levraging an orchestrator which is n8n  in our case. N8N is a system of nodes that each execute different instruction to acheive automations. These nodes are exported as a JSON object and thus version controlling is acheived by
updating and backing up the json files. 

Testing and development for this integration will be executed within a local docker container which will then be exported and pushed to Github for version controlling.
