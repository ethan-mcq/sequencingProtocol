# Sequencing Protocol
## 1. Experimental Design and Documentation
Click the link attached below. It will lead to a google form, in which it will ask for the following:
1) The current date, time started, and name.
2) What is your research question for this sequencing run? (This includes oligo pool if running OligoHyb and other general run info)
3) Special notes (ie. changes in reagents, concentrations, etc.)
5) Which sequencer will be used?

### Click on this [link](https://forms.gle/iGLwvJUjCKPqo7Mf8)

## 2. Sequencing Machine Settings
Once 'Start Sequencing' has been selected on the MinKNOW device, you will be met with a screen like this. Fill out the 'Experiment Name' section in the format: YYMMDD-EXPERIMENTNAME-MEMBERNAME. Where experiment name is the type of protocol followed (ie. cfDNAOligoHyb, Whole Genome, or GenomicOligoHyb) and MEMBERNAME is your name. SampleID will always be 1.

![alt text](https://github.com/ethan-mcq/sequencingProtocol/blob/main/steps/1-1-name.png?raw=true)

Once you have filled out those sections, you will select the 'Load settings from template' button to select the correct run settings. Click the template name that matches your EXPERIMENTNAME that you chose in the previous step. Once you select the correct template, select 'Load', then 'Skip to final review'. Here you can tehn begin sequencing. 

![alt text](https://github.com/ethan-mcq/sequencingProtocol/blob/main/steps/2-template.png?raw=true)

### 3. This section is to be followed only if a template is not available, otherwise move to step #4
If a template cannot be found that matches your EXPERIMENTNAME, these settings are generally acceptable for our lab; however, please contact Ethan McQuhae or Jordan Moore before beginning the run to verify.

![alt text](https://github.com/ethan-mcq/sequencingProtocol/blob/main/steps/3-lsk.png?raw=true)
![alt text](https://github.com/ethan-mcq/sequencingProtocol/blob/main/steps/4-runsettings.png?raw=true)
![alt text](https://github.com/ethan-mcq/sequencingProtocol/blob/main/steps/5-basecalling.png?raw=true)
![alt text](https://github.com/ethan-mcq/sequencingProtocol/blob/main/steps/6-rawreads.png?raw=true)

## 4. Run Monitoring
It is required that you monitor your run for at least 20 minutes after beginning. An initial 'Pore Check' will be carried out on the flow cell to check for viable pores. You will aim to have the following amount of pores on new flow cells:
| Flow cell | Min # Pores |
| --------- | ---------- |
| PromethION |  3000 |
| MinION |  900 |
| Flongle |  65 |
If your new flow cell has less than this, please discuss with Dr. Hill or Dr. Jenkins. 

Once sequencing has begun you will notice an array of flashing squares, these are the pores and will show you which ones are sequencing. Click the button that says 'Show more'. On the right side, you want to keep and eye on the number of pores who's state is 'Sequencing'. This number should steadily increase and plateau during the 20 minutes of observation. If for some reason the number beings to decrease or stays at an abnormally low number, please contact Dr. Hill or Dr. Jenkins. 

![alt text](https://github.com/ethan-mcq/sequencingProtocol/blob/main/steps/7.png?raw=true)

It is most important to stop the run as early as possible if something seems wrong, as you will be able to pull off your library and continue sequencing on a different flow cell if the first one is the problem. 
## 5. Raw Data Access
Once the run has completed either Jordan Moore or Ethan McQuhae will upload it to the Research & Development Google Drive folder. To access raw data, please refer to the drive to download your data. 
