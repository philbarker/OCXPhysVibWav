~~H~~
!!! note "about this site"
    Testing [OCX](https://k12ocx.github.io/k12ocx-specs/) with [MIT OCW Physics III -- Vibrations and Waves](https://ocw.mit.edu/courses/physics/8-03sc-physics-iii-vibrations-and-waves-fall-2016/).

[Source](https://github.com/philbarker/OCXPhysVibWav) on github. View output of embedded JSON-LD in Google's
<script>
text  = 'structured data testing tool'
here = window.location.href
sdd  = 'https://search.google.com/structured-data/testing-tool'
href = sdd+'#url='+encodeURIComponent(here)
link = '<a href="'+href+'">'+text+'</a>'
document.write(link)
</script>
~~/H~~
~~S ocxCourseOverview~~
---
'@id': '#Course'
'@type': Course
name : 'Physics III: Vibrations and Waves'
description : 'Vibrations and waves are everywhere. If you take any system and disturb it from a stable equilibrium, the resultant motion will be waves and vibrations. Think of a guitar string—pluck the string, and it vibrates. The sound waves generated make their way to our ears, and we hear the string’s sound. Our eyes see what’s happening because they receive the electromagnetic waves of the light reflected from the guitar string, so that we can recognize the beautiful sinusoidal waves on the string. In fact, without vibrations and waves, we could not recognize the universe around us at all!'
courseCode: 8.03
provider: MIT
educationalAlignment :
  '@type': AlignmentObject
  alignmentType: educationalLevel
  targetName: undergraduate
isBasedOn :
  '@type': Course
  url : https://ocw.mit.edu/courses/physics/8-03sc-physics-iii-vibrations-and-waves-fall-2016/
  creator : Yen-Jie Lee
  license : https://creativecommons.org/licenses/by-nc-sa/4.0/
license: https://creativecommons.org/licenses/by-nc-sa/4.0/
publisher :
  '@id': http://people.pjjk.net/Phil#id
  '@type': Person
  name: Phil Barker
audience  :
  '@type': EducationalAudience
  educationalRole: student
  description : Undergraduate student
hasPart :
  - {'@id': '#ocxCourseOverview', name: Course Home}
  - {'@id': 'syllabus#Syllabus',  name: Syllabus}
  - {'@id': 'instructorInsights#A',  name: Instructor Insights }
  - {'@id': 'ptI#Unit', name: 'Part I: Mechanical Vibrations and Waves' }
  - {'@id': 'ptII#Unit', name: 'Part II: Electromagnetic Waves' }
  - {'@id': 'ptIII#Unit', name: 'Part III: Optics' }
  - {'@id': 'finalExam#Assessment', name: Final Exam }
oer:Syllabus : {'@id':'/syllabus/#Syllabus',  name: Syllabus}
oer:mainContent : {'@type': webSite, url:'https://ocw.mit.edu/courses/physics/8-03sc-physics-iii-vibrations-and-waves-fall-2016/'}
---
---
'@id': '#Course'
'@type': 'WebPageElement'
hasPart :
  - {'@id': '#ocxMeta'}
  - {'@id': '#ocxDesc'}
---
~~H ocxMeta~~
# Physics III: Vibrations and Waves
![A water drop and a water column with waves below it](https://ocw.mit.edu/courses/physics/8-03sc-physics-iii-vibrations-and-waves-fall-2016/8-03scf16.jpg)

 * **Instructor**: Prof. Yen-Jie Lee
 * **Level**: Undergraduate
 * **License**: CC:BY-NC-SA
~~/H~~
~~S ocxDesc~~
## Course Description
Vibrations and waves are everywhere. If you take any system and disturb it from a stable equilibrium, the resultant motion will be waves and vibrations. Think of a guitar string—pluck the string, and it vibrates. The sound waves generated make their way to our ears, and we hear the string’s sound. Our eyes see what’s happening because they receive the electromagnetic waves of the light reflected from the guitar string, so that we can recognize the beautiful sinusoidal waves on the string. In fact, without vibrations and waves, we could not recognize the universe around us at all!

The amazing thing is that we can describe many fascinating phenomena arising from very different physical systems with mathematics. This course will provide you with the concepts and mathematical tools necessary to understand and explain a broad range of vibrations and waves. You will learn that waves come from many interconnected (coupled) objects when they are vibrating together. We will discuss many of these phenomena, along with related topics, including mechanical vibrations and waves, sound waves, electromagnetic waves, optics, and gravitational waves.
~~/S~~
~~N ocxNav~~
<a href="syllabus" rel="Next">Get started</a>
~~/N~~
~~/S~~
