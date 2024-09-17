class BackendAndAIEngineer {
  constructor() {
    this.name = "Ridwan Bakare";
    this.spokenLanguages = ["en_US"];
    this.roles = ["Backend Engineer", "AI Engineer"];
    this.mainSkills = ["JavaScript", "TypeScript", "TensorFlow", "scikit-learn", "Python", "Web3"];
    this.architectures = ["MVC", "Serverless", "Microservices", "Web3", "Neural Network Architectures", "Stream Processing"];
  }

  static sayHi() {
    console.log("Welcome to my profile! I'm a Backend & AI Engineer passionate about scalable systems and innovative AI solutions.");
  }
}

const me = new BackendAndAIEngineer();
BackendAndAIEngineer.sayHi();
