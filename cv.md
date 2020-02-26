# Andrey Dorofeev

# Contacts:
* phone number: 
* e-mail: dorfandy@gmail.com

# Summary

I've been working at Central Research Institute of Chemistry and Mechanics as an engeneer and lead engeneer since November 2008.

I really enjoy coding and want to work and keep growing in the mobile/backend field. I don't have any experience but I spend my free time making some pet-projects.

# Skills

* Swift
* Objective-C
* MVC, MVVM
* Cocoa Pods
* Alamofire, SwiftyJSON, Snapkit
* Firebase, Realm
* DJANGO
* Figma
* UI

# Code examples

    class ExpertiseRealmObject: Object {
        @objc dynamic var title: String = "Default"
        @objc dynamic var expert: String = "Expert"
        let items = List<ExpertiseItemRealmObject>()

        func toExpertise() -> Expertise {
            let expertise = Expertise()
            expertise.title = self.title
            for itemRealmObject in self.items {
                let item = itemRealmObject.toExpertiseItem()
                expertise.items.append(item)
            }
            return expertise
        }
    }

# Experience

My expirience is based on online cources and lectures and recomendations from a good friend of mine. 

Example of our pet-project includes the usage of github: https://github.com/unTramp/Cards

# Education

Higher education: Moscow Humanitarian Technical Academy

Online cources: Lynda, Treehouse, LetsBuildThatApp, Alex Skutarenko, Raywenderlich

Resources: Stackoverflow

# English
