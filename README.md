Gluon Community Packages for v2014.4
====================================

In this repository you can find packages, which are compatible with gluon 2014.4.

List of packages:
-----------------
* gluon-luci-wifi-config
  * this packages provides a tab in expertmode where you can dis/enable the SSIDs of your Router. This is verry usefull, when you want a router to mesh only on one band or if you want to create a  backbone router.

Concept of this repository (Will be translated soon):
-----------------------------------------------------
 * Ein Git-Repo in dem alle Pakete drin sind die nicht zum Kernsystem gehören
  * Kernsystem-Pakete sind Pakete die von neoraider und tcatm gepflegt werden
  * Alle anderen Pakete (z.B privat-wifi, wifi-config) sind addons
  * wird von mehreren Head-Maintainern verwaltet (DO9XE & pberndro)
  * für jede Gluon Version wird ein eigener Branch angelegt, um backports zu ermöglichen
 * Jedes Paket hat einen Maintainer, dieser kann gewechselt werden. hat ein Paket keinen Maintainer mehr und es findet sich kein neuer wird der Support ab dem Zeitpunkt der Inkompatibilität mit Gluon gestoppt.
  * bei Jeder neuen Gluonversion werden die Maintainer der GUR Pakete rechzeitig benachrichtigt, um Pakete auf Kompatibilität mit dem neuen Gluon zu prüfen.
   * Ist ein Paket nicht mit der neuen Version kompatibel muss es nachgebessert werden, sonst wird der Support (vorrübergehend) eingestellt.
   * Support kann wieder aufgenommen werden, wenn ein kompatibles Paket geliefert wird.
 * Über Aufnahme in die GURs entscheiden die Head-Maintainer in hinsicht auf Funktion und Dopplungen.
 * Pakete werden wie gewohnt in der site.mk eingebunden, modules-file wird gestellt
 * evtl einen Paketmanager schreiben, der einzelne Pakete installieren kann, welche auch Updates überleben.
