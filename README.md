<p align="center">
  <img src="https://user-images.githubusercontent.com/77406076/194965121-18ad72a6-082b-4123-a6c3-54fd13e77da1.gif" 
        alt="Welcom to my profile" 
        width="439" 
        height="121" 
        style=".centerImage" />
</p>

<p><em>A bachelor student at the <a href="https://sc.edu/">University of South Carolina</a>, majoring in Computer Science with a minor in Media Arts.</br>
</em></p>

```swift
  import Foundation

  struct Person: Mappable {
      var name: String?
      var year: Int?
      var age: Int?
      var lookingForJob: Bool?

      mutating func mapping(map: Map){
          name <- map["Matthew Vinson"]
          year <- map[4]
          age <- map[21]
          lookingForJob <- map[true]
      }
  }

  extension Info {
      static let pronouns = ("He","Him")
      static let email = "mevinson@email.sc.edu"
      static let website = "www.mevinson.live"
      static let favColor = Color(red: 78 / 255, green: 63 / 255, blue: 78/255) //Lilac
  }

  func aboutMe() {
      let languages = ["Java", "C++", "C#", "Swift", "Python", "JS"]
      let frameworks = ["SwiftUI", "TensorFlow", "Pytorch", "MongoKitten"]
      var cloudPlatforms: Deque = ["AWS", "GCP", "Microsoft Azure"]
      let database = "MongoDB"

      var workExp = """
      Product Support Engineer at SIOS Technology Corp. primarily responsible for the Linux products. Main duties include \
      handling cases with customers, obtaining and analyzing Windows and Linux system logs, providing root-cause-analysis \
      to the customer, and sharing solution/workaround if needed. Other duties include code reviews, bug triage, \ 
      Salesforce maintenance/upgrades, customer license rehosts, creating solutions for the customer support portal, \
      QA testing, and much more. 
      """
  }
```

</br></br>
<h2>💻 Some stats 💻</h2>

![Matts's github stats](https://github-readme-stats.vercel.app/api?username=mevinson&show_icons=true&title_color=fff&icon_color=79ff97&text_color=9f9f9f&bg_color=151515)
