# Caldria Sales Cursor Plugin

Restricted sales CRM tools and reusable skills for Caldria Supply. The plugin connects to a public MCP endpoint, but access requires a private Bearer token entered through Cursor's encrypted plugin configuration.

## Safety boundary

The MCP can research and save leads, create approval-pending email drafts, read human-approved messages, sync inbound Gmail metadata, and save internal sourcing and landed-cost proposals. It intentionally exposes no tool to approve its own work, delete records, purchase products, change payment terms, or publish final customer quotes.

Every external email and commercial commitment requires human approval in the Caldria Admin dashboard.

## Install

Install from Cursor Marketplace, open **Plugins → Configure**, enter the Caldria MCP access token, and enable the five skills for the Caldria Sales Operator Bot. Never put the token in chat, source control, or a Bot file.

Website: https://caldriasupply.com