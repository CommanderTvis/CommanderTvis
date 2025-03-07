### Iaroslav Postovalov

```kotlin
val CommanderTvis = lazybones {
    about {
        name = "Iaroslav Postovalov"
        location = Germany.Bremen
        contacts {
            email = "postovalovya@gmail.com"
            linkedin = "linkedin.com/in/iaroslav-postovalov"
            github = "github.com/commandertvis"
        }
    }
    
    workExperience {
        job {
            company = JetBrains
            role = SoftwareDeveloper
            employmentType = PartTime
            locations = listOf(Armenia.Yerevan, Germany.Bremen)
            period = Period("Sep 2022", "Dec 2024")
            accomplishments = listOf(
                "Contributed to the development and enhancement of Kotlin on JVM by designing and implementing new language features",
                "Implemented @JvmExposeBoxed annotation for seamless integration of inline classes with Java",
                "Optimized performance of the Kotlin compiler backend",
                "Resolved issues related to Kotlin IR serialization",
                "Participated in renovating tests for the new K2 compiler, including running tests on Android platform"
            )
        }
        
        job {
            company = MiLaboratories
            role = SoftwareDeveloper
            employmentType = Internship
            locations = listOf(Armenia.Yerevan)
            period = Period("Jul 2022", "Aug 2022")
            accomplishments = listOf(
                "Developed an enhanced version of an internal library for data plotting based on lets-plot-kotlin",
                "Implemented a Kotlin DSL incorporating statistical and serialization features"
            )
        }
        
        job {
            company = JetBrainsResearch to MIPT
            role = StudentResearcher
            employmentType = Internship
            locations = listOf(Russia.Dolgoprudny)
            period = Period("Sep 2020", "Apr 2022")
            accomplishments = listOf(
                "Researched in Nuclear Physics Methods Laboratory focusing on non-accelerator particle physics, numerical simulations, and software development",
                "Developed KMath - experimental mathematical library in Kotlin",
                "Developed Communicator - RPC library prototype with high-order functions and idiomatic APIs"
            )
        }
    }
    
    education {
        degree {
            university = ConstructorUniversity
            program = "BSc in Software, Data and Technology"
            period = Period("Sep 2023", "Jun 2026")
        }
        
        degree {
            university = MoscowStateUniversity.Branch(Armenia.Yerevan)
            program = "Applied Mathematics and CS"
            period = Period("Sep 2022", "Jun 2023")
        }
    }
    
    honors {
        award {
            title = NationalTechnologyOlympiad.Winner
            organization = "HSE University (Moscow, Russia)"
            date = "Mar 2022"
        }
    }
    
    tech(
        core = listOf(Kotlin, Compilers, JVM),

        proficient = listOf(
            Java,
            C,
            `C#`,
            Git,
            Python,
            LibraryDevelopment,
            SoftwareDevelopment
        )
    )
}
```
