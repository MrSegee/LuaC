# LuaC
### LuaC: The Future of LuaU

## What Is LuaC
**LuaC** (short for *Lua Connected*) is a module made for **Roblox Studio** that allows scripts to communicate with each other **without** interference or the use of RemoteEvents.

---

## Documentation

### How To Import LuaC Into Your Scripts
1. Create a **ModuleScript** anywhere in **ReplicatedStorage**.  
2. Paste the **source code** into the ModuleScript.  
3. Load and Require the ModuleScript using `require()`.  

<img width="685" height="73" alt="image" src="https://github.com/user-attachments/assets/068bb280-fef3-46b6-b025-ebd9164f8897" />

---

### What Are Networks
**Networks** are connections between scripts — similar to invisible **RemoteEvents** that allow scripts to communicate seamlessly.
These **Networks** help you transfer events, variables or any value from one script to another, keeping it nice and organised. Say **goodbye** to remote events!

---

### How To Set Up a Network
*(Assuming you have already imported LuaC.)*

1. **Create the network.**  
   To create a network, use the name you assigned to LuaC (in this example, `LuaC`) and call:  
   ```lua
   LuaC:CreateNetwork("NetworkName", script)
