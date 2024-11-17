# CedarML

CedarML is an XML-like markup language designed for structured AI interactions and dataset generation, particularly focused on fine-tuning language models and documenting tool-based conversations.

## Overview

CedarML provides a standardized format for capturing complex interactions between users, AI assistants, and tools while maintaining clear context and role attribution. The format is especially useful for generating high-quality training datasets and documenting interaction workflows involving multiple participants.

## Features

- **Structured Markup**: XML-like syntax with custom namespaces
- **Role-Based Communication**: Clear separation between different participants
- **Tool Integration**: Dedicated tags for tool input/output
- **Source Reference Management**: Structured citation and metadata handling

## Benefits
- Clear Separation of Concerns: Distinct tags for different interaction types
- Maintainable Hierarchy: Structured organization of data and metadata
- Context Preservation: Maintains relationship between different interaction elements
- Role Identification: Clear attribution of messages and actions

## Tag Structure

### Core Tags

```xml
<cedarml:tool-in.{toolname}>
    <!-- Tool input commands -->
</cedarml:tool-in.{toolname}>

<cedarml:tool-out.{toolname}>
    <!-- Tool output -->
</cedarml:tool-out.{toolname}>

<cedarml:role.user>
    <!-- User messages -->
</cedarml:role.user>

<cedarml:role.assistant>
    <!-- Assistant responses -->
</cedarml:role.assistant>

```

The format's strength lies in its ability to:
- Capture structured interactions
- Maintain context and relationships
- Support multiple types of data
- Enable clear role separation
- Support metadata and citations

These characteristics make it valuable in any scenario where:
1. Tool interactions need to be documented
2. Multiple roles are involved
3. Command interpretation is important
4. Context preservation is crucial
5. Structured data needs to be combined with natural language
6. Process documentation is essential

The format could be particularly powerful when adapted for scenarios requiring:
- Regulatory compliance
- Quality assurance
- Training and education
- Process improvement
- Knowledge transfer
- Automation development

