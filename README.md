This Blueprint will create two VMs:
    
    1. Ollama Server   ( https://ollama.com/download/linux )
    2. OpenWebGUI      ( https://docs.openwebui.com/ )

OpenWebGUI will be the Chat GUI for the LLM engine (Ollama server)

Requirements: Rockylinux image on Nutanix Cluster. I have used the Image available on Nutanix ublic SW Download "nkp-rocky-9.4-release-1.29.9-20241008013213.qcow2" but it should work with any Rockylinux 9 Linux distro.

On Ollama server you can add other LLM models from the ones available: https://github.com/ollama/ollama

