# Dev Notes - Kernel Selection Issue

## Problem ✅ RESOLVED
~~VS Code not showing "Amazon Bedrock AgentCore" kernel in the kernel selector dropdown.~~

**UPDATE**: User successfully selected the "Amazon Bedrock AgentCore" kernel in VS Code! 🎉

## Setup Completed
- ✅ Virtual environment created at project root: `venv/`
- ✅ All packages installed including `ipykernel`
- ✅ Jupyter kernel registered: `bedrock-agentcore`
- ✅ **Kernel successfully selected in VS Code**

## Kernel Selection Solutions

### Select Python Interpreter
1. Press **Cmd+Shift+P**
2. Type: `Python: Select Interpreter`
3. Choose: `/Users/kx/ws/amazon-bedrock-agentcore-samples/venv/bin/python`

## Verification
To confirm kernel is installed:
```bash
jupyter kernelspec list
```
Should show: `bedrock-agentcore    /Users/kx/Library/Jupyter/kernels/bedrock-agentcore`

---

## ✅ READY FOR NEXT STEPS:
- Run notebook cells with the proper kernel
- Test the AgentCore tutorial
- Deploy agents to runtime 