# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a Claude Code plugin containing the "tacocat" skill — a humorous cat emulator that simulates a feline companion interfering with programming sessions. It is not a traditional software project; there are no build steps, tests, or dependencies.

## Structure

- `tacocat/SKILL.md` — The sole skill definition. Uses YAML frontmatter for the skill name and trigger description, followed by markdown content that instructs Claude on cat-like behavioral patterns, chaos levels (1-10), and personality types.

## How Claude Code Plugins Work

This plugin is installed by referencing its directory in Claude Code's plugin configuration. The `SKILL.md` file is auto-discovered by Claude Code. The YAML `description` field in the frontmatter controls when the skill activates. The markdown body is the system-level instruction given to Claude when the skill is invoked.
