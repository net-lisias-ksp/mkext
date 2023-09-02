# net.lisias.ksp/mkext

C7's Mk 1, 2 and 3 Extensions for KSP from L Aerospace.


## About L Aerospace

A new kid on the block, plain simple. We came from nowhere and we don't know where we're going, but hey, we know how to fly to there fast!

We still have some landing surviving issues, but we're working on that.

**L Aerospace KSP Division: Boldly crashing what no Kerbal has crashed before.**


## Description

### In a hurry

* Mk1
	+ Mark1 Standard Cockpit, Civilian Version
	+ Mk1 Boarding Hatch
	+ Some specialised fuel tanks
* Mk2
	+ Some specialised fuel tanks
* Mk3
	+ Some specialised fuel tanks


## References

* Rationale and discussion about some problems this add-on solves (or creates):
	+ [Mk1 Crew Cabin needs a side door](https://forum.kerbalspaceprogram.com/index.php?/topic/136279-mk1-crew-cabin-needs-a-side-door/&page=2) (Forum Thread)
	+ [Why doesn't the Mk1 passenger module have a top hatch?](https://www.reddit.com/r/KerbalSpaceProgram/comments/3tfll9/why_doesnt_the_mk1_passenger_module_have_a_top/) (Reddit)
* [Mk1-Cabin-Hatch](https://github.com/skalou/Mk1-Cabin-Hatch)
	+ inspiration for implementing some tricks

## Known Issues

* There're some legal issues I need to cope.
	* I just copied and paste configs from Stock. I shuold had used Module Manager's copy operator to do that.
	* It would make things a lot easier too, as it would earn for free any changes from the Stock settings.
	* Until I do it, please don't redistribute any of this - let's do the right thing, okay?
* Mk1 Cockpit Civilian
	* The Pilot's SelfieCam is out of place (the console is on the way)
	* The cabin's lights are not working. I messed up the GLOW UV mapping somehow.
	* Jump Seat
		* The Jump seat mesh ideally should be a simplified one, not a full featured seat. 
		* The kerbal's eyes view revealed some glitches on the cockpit mesh. I don't remember messing up with the vertices, however - perhaps a legacy mesh error that was never discovered before?
		* That half baked measure to hide the hatch's hole on the fuselage also need some caring...
* Mk1 Boarding Hatch
	* The cabin's lights are not working. I messed up the GLOW UV mapping somehow.
	* Some of my aircrafts are being locked by some reason when I use the Boarding Hatch. But I'm not sure if this is my fault or some mod stomping my feet.
	* The Seat mesh ideally should be a simplified one, not a full featured seat (as it is intended for crew use, as in a real aircraft)
	* The Boarding Hatch meshes need some work too.
		* The external hatch probably should be higher (and bigger?) 
		* The Mask and Overlay are cropping the wrong side
		* Need to get rid of a window in the internal view
			* And add a 90° Hatch	 
* Some of my aircrafts are being locked by some reason when I use the Boarding Hatch and/or Civilian Cockpit. But I'm not sure if this is my fault or some mod stomping my feet.
* Perhaps remove all internal hatch, creating open spaces? We are talking about civilian, atmospheric only, aircrafts after all - no need to be orbit proof.
	* Not sure if it would work with the internal view... 
* Mk1 Oxidizer Tank
	* That "high pressure" stunt didn't cut it. =P
	* Need some better story to justify that 10% extra capacity, or perhaps a better balance for the feature. :-D

## License

This work is licensed under [SKL 1.0](http://ksp.lisias.net/SKL-1_0.txt).

- - - 

See also:

* Thread on KSP Forum.
* L Aerospace KSP Division
	+ [Home Page](http://ksp.lisias.net/)
	+ [Research & Development Headquarters](https://github.com/net-lisias-ksp)
