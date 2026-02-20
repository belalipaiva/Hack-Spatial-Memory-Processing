# Hack-Spatial-Memory-Processing

## Dataset usage restrictions

The dataset provided in this repository is **UNPLUBISHED DATA** and is made
available **exclusively for use within the context of HACKATHON POTENTIAL**.

The dataset:
- may be used **ONLY FOR HANDS-ON ACTIVITIES DURING THE HACKATHON POTENTIAL (from:20/02/2026-28/02/2026)**
- may **NOT** be reused, redistributed, modified, or shared
- may **NOT** be used for research, publication, or derivative works
- may **NOT** be retained after the event

All rights to the dataset are reserved by the authors. 

Data and example notebook can be accessed trough this page: **https://drive.google.com/drive/folders/14mSP5zmwj7ukhmhGYxlaYCjFgI8mt2Xp?usp=drive_link**
Access will be released upon request.

The CODE in this repository is released under the MIT License.

Project description : 

Memory processing under aversive conditions in the hippocampus-amygdala network

  Mnemonic functions allow us to connect new experiences to prior knowledge—in other words, they enable continuous learning and development of new skills as well as adaptive behaviors. As you may have experienced, emotional states can influence the formation of new memories. Despite this clear link between emotional stages and memory, a crucial question remains: How do emotions impact the consolidation of new memories? One brain circuit that is implicated in both emotional and mnemonic processing is the **hippocampus-basolateral amygdala axis**. Studies have shown that the BLA mediates the impact of stress on dorsal hippocampus (dHPC) activity and, through coordinated activation/reactivation patterns with the dHPC, forms a representation of potentially threatening locations. Interestingly, the BLA has no direct connections with the dHPC, but it does have direct connections with the ventral hippocampus (vHPC). Studies have shown that the vHPC is crucial for emotional processing. Therefore, the interplay among these three brain regions may underlie the consolidation of memories with associated emotional valence.

<img width="1478" height="888" alt="image" src="https://github.com/user-attachments/assets/67778a77-3b75-4973-8b38-7362bcde589b" />

**Available Data**

In this project, you will have access to neuronal activity data from three different brain subregions:
**Dorsal Hippocampus (dHPC):** Primarily involved in processing contextual and spatial information;
**Ventral Hippocampus (vHPC):** Primarily involved in processing experiences with emotional valence;
**Basolateral Amygdala (BLA):** A key structure for emotional processing. 
For each of these three areas, you'll have access to:
Sleep stages (REM and NREM) are of particular interest, as memory consolidation and emotional regulation are thought to occur primarily during sleep and quiet rest periods; these data epochs are of high interest in this dataset.
**Local Field Potentials (LFPs):** Mean electrical signals representing the resultant activity of neurons surrounding recording sites; 
**Single-cell activity:** Precise spike times from individual neurons near the recording sites.

<img width="1374" height="994" alt="image" src="https://github.com/user-attachments/assets/dacfe394-d226-4652-8c46-7dde95cbd96e" />

Below is an example of the data table you will have access to:

<img width="2460" height="1050" alt="image" src="https://github.com/user-attachments/assets/a627d9df-ff7e-4f37-afcf-133c92eae561" />

**The experiment**

To investigate the interactions between these brain regions and address our research question, the following experiment was conducted in Rats:
**Sleep/Rest phase 1:** Rats' sleep was recorded before the learning task and can serve as a reference for investigating changes in sleep that may emerge after the learning sessions.  

**Learning Phase:** Rats were trained on a cheeseboard maze (a large, open platform) to find water rewards. During each session, rewards were always located at the same positions but changed across days, requiring the rats to learn and remember a new set of reward locations each day.

**Sleep/Rest Phase 2:** Following the maze-learning session, brain activity was recorded during sleep and rest periods. Signs of memory consolidation may be observed in neural data during this period.

<img width="1706" height="876" alt="image" src="https://github.com/user-attachments/assets/5405ff22-9bd4-418f-9885-810a3f1efb13" />

Finally, to explore the role of emotional valence on the consolidation of a new memory, the experiment was repeated under two conditions:
Neutral condition: Standard learning without threatening input; 
Aversive condition: Rats received unpredictable, mild eyelid shocks while in the maze, creating a stressful learning environment.

**Your Mission**

As a team in this hackathon, your goal is to investigate how the learning phase affects brain activity during sleep and whether this effect differs under stressful conditions. Here is a list of ideas:
Starting point:

Look for patterns of co-activation, or coupling patterns between different brain regions that appear during Sleep II but not during Sleep I. 
These could represent memory consolidation processes.                                                                                                                                                    
**Advanced analysis:** 

If you're feeling confident, try to identify these patterns during the Learning phase itself, then demonstrate that they were "replayed" or reactivated during Sleep II—this would provide evidence for memory consolidation.
Do specific brain regions show increased synchronization after learning?
Are there differences in neural replay patterns between neutral and aversive conditions?
Do specific oscillatory rhythms (theta, gamma, ripples) change after learning?
How do single-cell firing patterns change between Sleep I and Sleep II?

**Technical Details for the Curious**

**What are Local Field Potentials (LFPs)?** LFPs represent the summed electrical activity of many neurons in a local region of brain tissue. They primarily reflect synaptic currents and are particularly useful for identifying rhythmic patterns of neural activity (oscillations) that coordinate activity across brain regions.

**How are LFPs and spikes recorded?** Data were recorded using silicon probes—thin electrode arrays that can simultaneously record from multiple brain regions and depths. These probes contain multiple recording sites along their length, allowing us to sample activity across different cortical layers.

**What exactly are single-cell spikes?** Spikes (or action potentials) are the individual firing events of single neurons. By analyzing spike times, we can determine when individual cells are active and how they coordinate their activity with other neurons.

**How were sleep stages determined?** Sleep stages were classified by analyzing theta rhythms (7-12 Hz oscillations) in the dHPC LFP:
  - REM sleep: High theta power, associated with dreaming in humans and specific emotional memory consolidation processes;
  - NREM sleep: Low theta power, associated with slow-wave sleep and different consolidation mechanisms such as the occurrence of sharp-wave ripples and cellular reactivation.

Project description written by LIMA-PAIVA Izabela in collaboration with Baptist Lorenzi

In case you have any questions about the dataset or research question introduced here, contact: izabela.lima-paiva@inserm.fr
