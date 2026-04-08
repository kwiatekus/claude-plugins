# claude-plugins

A collection of Claude Code plugins maintained by the Kyma team.

## Available plugins

### doc-issue

Writes user documentation for a given GitHub issue URL, following Kyma content guidelines (style, formatting, terminology, topic types).

## Setup

**1. Add this marketplace to Claude Code:**

```
/plugin marketplace add kyma-project/claude-plugins
```

**2. Install the plugin you want:**

```
/plugin install doc-issue
```

## Usage

### doc-issue

Invoke the plugin with a GitHub issue URL:

```
/doc-issue https://github.com/kyma-project/kyma/issues/123
```

Claude Code will analyze the issue and generate documentation following Kyma content guidelines.