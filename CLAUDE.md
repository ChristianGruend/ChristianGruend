# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Purpose

This is a **GitHub profile repository** for Christian Gründer — it renders as the user's GitHub profile page. The primary content is `README.md`, which is the profile document displayed publicly.

## Repository Structure

- `README.md` — GitHub profile page (profile bio, tech stack, projects, contact)
- `Pop_OSconfig/` — Git submodule (currently uninitialized) for Pop!_OS system configuration

## Active Projects Referenced

- **Jarvis117** — A locally running vLLM-powered AI assistant in Docker (emails, file management, web research)
- **AI Security Automation** — AI-driven security checks integrated into DevOps pipelines using Terraform

## Tech Context

Owner's stack: AWS, Terraform, Docker, Kubernetes, CI/CD, Bash, Python, Linux/WSL, Git. Focus area: AI Security and LLM-based automation (vLLM).

## Development Notes

There is no build system, test runner, or linter configured — this is a documentation-only repository. Changes are primarily edits to `README.md`.

When working on the `Pop_OSconfig` submodule, initialize it first:
```bash
git submodule update --init --recursive
```
