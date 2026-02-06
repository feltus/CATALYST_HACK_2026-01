# CATALYST HACKATHON (2026-01-30)::: Testing the Palmetto2 bioLLM infrastructure prototype.

## Invitees 
RCD: Carl E Ehrett <cehrett@clemson.edu>  
RCD: Doug Dawson <dndawso@clemson.edu>  
RCD: Zachary Ian Gerstner <zigerst@clemson.edu>  
BIO: Xusheng Ai <xai@clemson.edu>   
BIO: Tzu-Yu Chu <tzuyuc@clemson.edu>  
BIO: Gabriel Serrano <gserran@clemson.edu>  
BIO: Sarah Moorshead <smoorsh@g.clemson.edu>  
BIO: Maura Korte <mjkorte@clemson.edu>  
BIO: Macy Rietz <mrietz@g.clemson.edu>  
BIO: Varun Sethi <vsethi@g.clemson.edu>  
BIO: Alex Feltus <ffeltus@clemson.edu>  

## Background 
Members of the CCIT-RCDE division and faculty from Clemson Genetics & Biochemistry Department, Chemical and Biomolecular Engineering Department, Electrical and Computer Engineering department and the School of Computing have joined forces to create modular poly-domain research generative AI ecosystem (Hub-Spoke model) on Palmetto2 called Clemson Advanced Computational Analytics and Learning for Integrated Science Translation (CATALYST--possible system name).

Phase one of CATALYST development is applying the OpenAI system on Plametto2 (codex, MCP server, vLLM) to build a Life Science research facet called bioLLM (placeholder name).

bioLLM builds upon recent advances in biological foundation models, Stanford's Biomni framework, and openAI LLM middleware (codex, MCP server), the team has created an extensible, locally-deployed AI platform prototype operating on Clemson's Palmetto2 HPC cluster. The ecosystem addresses current limitations in fragmented bioinformatics tools, scalability, security, and sustainability. Through an innovative agentic framework, Clemson researchers will gain access to specialized bioLLMs for genomics, transcriptomics, proteomics, and systems biology applications.   

In order to facilitate usage and harden this system, we will be hosting hackathons in 2026 with exclusive access to alpha test bioLLM ecosystem.  The first hackathon will be a small group of hackers that will test prompt the agentic bioLLM system to perform scientific discovery, usage documentation, and identify gaps in the system.  

## When & Where
The first Hackathon will be a week-long asynchronous event from Jan 30 (Fri) - Feb 6 (Fri).   
There will be synchronous Zoom meetings 9am-10am each Friday: https://clemson.zoom.us/j/9452064261   
Feltus will be in Zoom 9am to noon each day.   

## Collaboration. 
Discord server invite: https://discord.gg/4QU39zjs  
Discord server URL: https://discord.com/channels/1461097829706760202/1461097830239305923

## Pre-Hack  
1.	Obtain OpenAI account with your clemson.edu email (not g.clemson.edu)
2.  Install codex with https://git.rcd.clemson.edu/biollms/biocodex
3.  Run some test prompts.

## Hackathon Charge 
You have two choices:

1. Design and test an experimental workflow to test a biological hypothesis using the bioLLM system. Prepare a report on what you found and how you found it (document your prompts!).
2. Develop a new tool for bioLLM to access.

In concert, you will test the OpenAI LLM and bioLLM agent ability to generate useful biological results from existing tools. Gaps will be documented and submitted as issues at https://git.rcd.clemson.edu/biollms/biocodex. 

## Issue Framework
Description of the task and problem  
What LLM model did you use?
What was your prompt 
Paste errors or description of incorrect results.
(optional) Performance metrics 

## Example Computatioanl Biology Workflows
https://github.com/feltus/InSilicoDiseaseHypothesis  
https://github.com/feltus/lab-drug-targeting  
https://github.com/feltus/identifying_differentially_expressed_genes  
https://github.com/feltus/biohackathon-finding-dna-eqtls-underlying-a-disease  

## Available Tools 
Genomics.py --- biomni
DNAbert2  foundation model
Zach's Pipeline (TBD)  
#(Docking) --- biomni  
#Genomics.py --- biomni
Build your own tool!  The tool standard is defined here: TBD.

## Rewards 
(1) Early access to Palmetto2 LLM infrastructure. 
(2) Possible co-authorship on a PEARC or other manuscript

## To Do

### Feltus Lab
* Build Gabe's BLAST Tool/Compare with extant Biomni tool (eg.g alignments, phylogenetics)
* Fix Sarah's API problem for GWAS  
* Compare Tzu-Yu scRNAseq annotations with a bimni tool (or drop?)  
* Check Varun's Fisher Exact Test results 
* See what Maura achieved  

### End User Documentation
* Tool format and installation documentation
* Genomic Data access bestpractices,workflow,documentation
* Bio API bestpractices,workflow,documentation
* General workflow documentation for a Python/bash iterate user:  
**    ExperimentalDesign>>>InputDataCollection>>>Algorithm(Code)>>>Results
**    Validation( common sense, +/- control . literature)  
**    Pitfalls(codex uses wrong envirnoment, etc.)  
**    Log Parsing (MethodsforReproducibility, AI Suggestions for better experiments; https://tools.s-anand.net/codexlog/) 
**    Workfing Directory directory sstructure (input_data, code, results, methods, logs) 

### Back end improvements
* RAG functionality
* Test foundation model tools (DNABERT, etc.)

### Workshops and Funding
* Come up with name for hub and spoke system instaed of codex or bimni  
* 4-lab Bio workshop    
* Materials workshop   
* Fall Hacakthon (OpenAI sponsered?; HPC, Laptop, custom GPTs)  
* Huge RFP  

## Next Workshops 
* March 6: (Hack2) Biology tool development for Palmetto2 biology LLM infrastructure (Expand to Birtwistle, Huang, and Smith labs)  
* April 3: (Hack3) Materials tool development for Palmetto2 materials LLM infrastructure  

