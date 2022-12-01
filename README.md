# sonotexto-quark
This quark contains the SonoTexto, SampleTexto, and Ptexto classes developed with SuperCollider as part of Hernani Villaseñor's Ph.D. research project in [Music Technology UNAM](https://www.posgrado.unam.mx/musica/).  
**SonoTexto:** records and saves sounds in the \<sonotexto> folder.  
**SampleTexto:** reads sounds from a folder by their index number and creates a SynthDef for each mono and stereo sound in the folder.  
**Ptexto:** is a SuperCollider pattern based on the module operation.  
	
# Installation
1 Download the quark and place it in the quark or downloaded-quarks folder in Extensions.   
2 Create two folders with the name \<sonotexto> and \<sampletexto> and place them in the Recordings path of SuperCollider.

# Install the quark inside SuperCollider IDE
1 Open SuperCollider.  
2 Declare this line:
```
Quarks.install("https://github.com/hvillase/sonotexto-quark.git")
```
