**OpenIntelligence Natural Language Interface Rules Server 1.0 (Fremium version)**
Copyright (C) 2024 Ideasol Australia Pty Ltd (trading as OpenIntelligence). All Rights Reserved. 

## Introduction
Welcome to the OpenIntelligence Natural Language Interface for Splunk.
Our natural language interface allows both novice and experienced Splunk users to search for information or define complex correlation rules in their own language. 
This repo contains the freemium version of the Open Intelligence Natural Language Rules Server. The rules server hosts most of the intelligence of the system and exposes the rest of the API used by the NL Interface Splunk app. We also offer trial, shared and custom production licences in a self-hosted instance of this rules server (see below).

## Versions and Licenses
OpenIntelligence currently offers four different Rest API/SW licenses:
- ** Freemium Licence ** provides access to an executable with a limited version of the Rest API. This is the license that applies to this project.
- ** Trial Licence ** provides temporary access to our own Rules Engine development instance the Rest API of our . This license is for evaluation purposes only and also has a limit on the number of daily queries.
- ** Shared Production License ** provides access to the Rest API of our shared Rules Engine Production instance and includes OpenIntelligence standard support. 
- ** A Custom Production Licence ** provides access to a dedicated and customized Rules Engine Production instance with several hosting and support options.
Please contact us at info@openintelligence.com.au for more details and how to request any of these licences.

## Dependencies
All executables has the following dependency:
- SWI Prolog: https://www.swi-prolog.org/
If you installing SWI-Prolog in Windows, please select one of the system PATH options.

## Install Instructions (Windows)
- Install SWI Prolog
- Checkout/download the **rules_server_no_console.exe** executable.
- Run the executable **rules_server_no_console.exe**
  The Prolog console should appear. You might get an antivirus warning the first time you run this command (you could run the antivirus on the file to confirm does not contain a virus).
- Enter **startServer.** in the Prolog console.
  The message **% Started server at https://localhost:10000/** will be displayed
- To stop the server enter **server:stop(10000).** and then **halt.**


