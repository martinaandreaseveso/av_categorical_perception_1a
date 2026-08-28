*av_categorical_perception_1a

**Contributors**
Martina Andrea Seveso,
Rebecca Hirst,
Alan O'Dowd,
Fiona N. Newell

**Research aims**

To investigate the nature of multisensory categories and the categorization of 3D familiar objects.

**Research questions**

1. Does multisensory information affect the categorisation of 3D familiar object?
2. Does the exposure to audio-visual objects’categories influence the categorization of corresponding visual stimuli?

**Method and Procedure**

The study is develop in PsychoPy (version 2022.2.5; Peirce et al., 2019) and it is conducted online via Pavlovia and Prolific.

[Peirce, J. W., Gray, J. R., Simpson, S., MacAskill, M. R., Höchenberger, R., Sogo, H., Kastman, E., Lindeløv, J. (2019). PsychoPy2: experiments in behavior made easy. Behavior Research Methods. 10.3758/s13428-018-01193-y]

The experiment comprises two phases, with a self-timed break between the two:

1. Learning Phase - bimodal: a learning task, where visual objects are paired with semantically congruent, incongruent sounds and then participants performed a 2-alternative forced-choice (2-AFC) task in which they had to decided, on each trial, if the stimuli have already been presented or it is (e.g., old new recognition task). Participants must achieve 80% accuracy to proceed, with 3 repeats to reach the threshold.
2. Categorical Perception Phase - unimodal visual: visual discrimination task followed by a categorization task, with self-time breaks between the tasks. The categorization task led to determine the subjective category boundary for each object pair, thus, it is always presented after the discrimination task to avoid any bias during the latter.

The presentation order of objects continua is randomised across participants.

**Stimuli
**
The experiment presents 3D objects shapes of familiar objects paired either with semantically congruent, incongruent, irrelevant sounds or presented only visually.

_3D Visual stimuli_ : The 3D objects shapes are created though the software SketchUp Pro (www.sketchup.com).

1. Development of 2D shapes for each object, with a maximum height of 100 mm and width of 70 mm.
2. From 2D to 3D: The 2D shapes are then rotated along the vertical axes to create the 3D object. All the objects have been created to fill a cylinder of 100x70mm to maintain the same physical proportions.

The list of object categories (including the two exemplars) developed: Bell (Hand, Church), Bottle (Wine, Coke), Glass (Wine, Beer), Vases (Urn, Single Stem), Lamp (Bedside, Desk), Stationary (Pen, Highlighter), Phone (Smart, Home), Clock (Wall, Wrist). See Image 2 for an example of 3D object developed.

_Morphing procedure: morphed continua_ : Identification of step number for each continuum (11 steps). For each object pair is developed a morphed continua of 11 stimuli, including the 2 poles and the 9 morphed objects within the two poles.

The morphing procedure is accomplished with the software Blender 3.5.0 (2023) (www.blender.org).

1. Each object pair is located the same 3D space. The Shrink wrap Modifier is applied on one of the two objects and the Shape Key is assigned to the other object, with minimum range of 0 to maximum of 1.
2. Every object in each object pair is created keeping constant the difference of 0.1 step from each other.
3. The stimuli are extracted form Blender 3.3.0 by keeping constant the camera viewpoint and the lighting condition. The render engine Workebench is applied to all objects, with specs Studio Lighting, Colour Material (0132, light grey) and Specular Lighting applied.
All the images are extracted with a resolution of 1080 x 1080 px, %100, and presented in a canonical view, on a transparent background.

_Auditory stimuli_ : Sounds are downloaded from online sound databases (e.g., Free Sounds Library, freeSFX, Storyblocks). All the sounds have a duration of 500 ms and a rate of 44100 Hz, duration and rate of the auditory stimuli was kept constant thought version 3.0.0 of Audacity® recording and editing software (https://audacityteam.org/).
The sound in both Audio-Visual Semantic Congruent and Incongruent Learning conditions are associated with the correspondent semantic congruent or incongruent object, respectively. Finally, in the Audio-Visual Irrelevant Learning condition, sounds of alphabet letter are paired with the correspondent letters: female voices were paired with capital letters, and male voices were paired with italics letters.

**Design**

The experiment is mixed-subejcts design.
**
Dependent variables**

1. Probability of categorising stimuli as belonging to category A.
2. Categorisation accuracy and RTs.
3. Discrimination accuracy and RTs.

**Independent variables**

1. Modality, stimulus and their interaction.
2. Modality, stimulus position and their interaction.

**Covariates**

Age, sex, and object type.

**Ethics**

Full ethical approval was obtained from the School of Psychology Ethics Committee, Trinity College Dublin.

**License**
a. Code (analysis scripts, stimuli generation): MIT License
b. All other materials (data, stimuli, experimental design): CC BY 4.0

All stimuli were created by the author (Seveso, M., A.). Data has been anonymised and contains no personal information.
