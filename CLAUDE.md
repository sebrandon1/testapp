# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

A simple Go test application for experimentation and testing purposes.

## Common Commands

### Build
```bash
go build -o testapp .
```

### Run
```bash
go run main.go
```

### Test
```bash
go test ./...
```

### Install Dependencies
```bash
go mod download
```

## Architecture

Single-file application with `main.go` at the repository root. Uses the Cobra CLI framework for command-line handling.

## Requirements

- Go 1.17+

## Dependencies

- `github.com/spf13/cobra` - CLI framework

## Code Style

- Follow standard Go conventions and formatting
- Use `go fmt` before committing
- Run `go vet` to catch common issues
