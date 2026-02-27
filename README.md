# reddit-comfyui-monitor
Public overview of a personal read-only Reddit monitoring workflow for r/comfyui


# Reddit ComfyUI Monitor

Public overview of a personal, non-commercial, read-only workflow for monitoring public posts from `r/comfyui`.

## Purpose

This project documents an external workflow used to monitor public discussions from `r/comfyui`, classify posts into useful categories, and generate a personal weekly summary for research and content planning.

## What it does

- Reads public post metadata and content from `r/comfyui`
- Classifies posts into categories such as:
  - News
  - Tutorials
  - Workflows
  - Help-needed
- Generates a weekly summary for personal use

## Scope

This project is:

- **Read-only**
- **Non-commercial**
- **Limited to public subreddit content**
- **Low-volume and rate-limit compliant**
- **Not used for posting, voting, commenting, or moderation**
- **Not used for user profiling**
- **Not intended to republish Reddit content as a substitute for Reddit**

## Platform

The production workflow runs externally in a private `n8n` automation environment hosted on personal infrastructure.

This repository is **documentation only** and does not expose:
- production credentials
- internal automation details
- private infrastructure
- secrets or tokens

## Devvit note

This use case does not run inside Reddit and is not an in-platform Reddit app experience. It is an external read-only workflow for monitoring and summarizing public subreddit posts.

## Status

Documentation-only public repository for API access review and project transparency.
