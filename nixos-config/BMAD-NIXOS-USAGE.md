# BMAD NixOS Expert - Usage Guide

## 🎯 Your Custom NixOS Expert Agent

I've created a specialized BMAD NixOS expert that integrates with the MCP-NixOS server and is tailored for your configuration needs.

### **✅ Ready to Use:**
- **NixOS Expert Agent**: `bmad-nixos-expert.md` (in your nixos-config directory)
- **MCP Integration**: Real-time package and option validation
- **Your Config Focus**: Optimized for your modular flake-based setup

## 🚀 Quick Start

### 1. Copy Agent to Claude/ChatGPT
```bash
# Agent is now in your nixos-config directory
cat bmad-nixos-expert.md
```

### 2. Use with Your Configuration
Copy the entire agent file to your AI platform and try this prompt:

```
I want you to analyze and optimize my NixOS configuration structure.

Current setup:
- Flake-based configuration with Home Manager
- Two machines: HP Pavilion (LXQt) and MSI Raider (KDE Plasma 6)
- Modular design with shared profiles and roles
- Hardware-specific modules for each machine

Goals:
1. Optimize build performance and reduce rebuild times
2. Improve modularity and code reuse between machines
3. Ensure security best practices
4. Streamline the update workflow

Please analyze my configuration and provide specific recommendations.

[Then paste your flake.nix and key configuration files]
```

## 💡 Specific Use Cases for Your Setup

### Configuration Analysis
```
Agent Task: optimize-config
Analyzes your modular structure and suggests improvements for:
- Build performance optimization
- Module interdependency reduction  
- Hardware abstraction improvements
- Security hardening opportunities
```

### MCP-Enhanced Features
With the MCP-NixOS integration, the agent can:
- **Validate package names** in your configurations in real-time
- **Check option compatibility** across NixOS versions
- **Suggest current package versions** for optimal performance
- **Detect deprecated options** and provide modern alternatives

### Multi-Machine Optimization
Perfect for your HP/MSI dual-machine setup:
- Shared module optimization
- Hardware-specific tuning recommendations
- Profile-based configuration improvements
- Home Manager integration enhancements

## 🔧 Available Commands

### Core Configuration Tasks
1. **optimize-config** - Analyze your current setup for performance and best practices
2. **review-flake** - Evaluate your flake.nix structure and dependencies
3. **security-review** - Audit configuration for security hardening
4. **multi-machine** - Optimize shared modules and machine-specific configs

### Development Tasks  
5. **create-module** - Design new modular components
6. **hardware-config** - Generate hardware-specific optimizations
7. **home-manager-setup** - Improve Home Manager integration
8. **troubleshoot-build** - Debug build failures and performance issues

## 📋 Example Prompts for Your Config

### Performance Optimization
```
Use the optimize-config command to analyze my NixOS flake setup.
Focus on:
- Reducing rebuild times between HP and MSI machines
- Optimizing shared module dependencies
- Improving Home Manager integration performance
- Identifying heavy packages that could be optimized

[Attach your flake.nix and key module files]
```

### Security Review
```
Run security-review on my configuration with focus on:
- SSH key management across machines
- User privilege separation
- Network security for home lab environment
- Service hardening for development workstations

Current context: HP laptop and MSI gaming laptop, both used for development
```

### Module Architecture
```
Help me improve my modular architecture using create-module.
Current structure: profiles/, roles/, shared/, hardware-specific modules
Goal: Better abstraction and easier maintenance
Target: Add new machine types without duplicating configuration
```

## 🔗 MCP-NixOS Server Benefits

When you have MCP-NixOS server running, the agent becomes much more powerful:

### Real-Time Validation
- Verifies package names exist before recommending
- Checks NixOS option compatibility
- Validates Home Manager options

### Current Information
- Latest package versions and security updates
- Deprecated option warnings
- Performance impact assessments

### Smart Suggestions
- Context-aware package alternatives
- Version-specific optimization tips
- Hardware-specific recommendations

## 📁 Integration with Your Workflow

### Before Configuration Changes
1. Use agent to analyze proposed changes
2. Get security and performance impact assessment
3. Receive testing recommendations

### During Development
1. Validate new modules before integration
2. Check package compatibility
3. Optimize for your specific hardware

### After Updates
1. Review changes for optimization opportunities
2. Ensure security posture maintained
3. Document architectural decisions

## 🎯 Perfect Match for Your Setup

This NixOS expert is specifically designed for users like you who:
- ✅ Use flake-based configurations
- ✅ Manage multiple machines with shared configs
- ✅ Value modular, maintainable architectures
- ✅ Want performance optimization
- ✅ Need security best practices
- ✅ Integrate Home Manager effectively

**Try it now with your actual configuration files for immediate, actionable improvements!**
