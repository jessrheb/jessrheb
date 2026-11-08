```
class SoftwareEngineer {
  readonly firstName: string = 'Jessicah';
  readonly role: string = 'Technical Assistant';
  readonly company: string = 'CESAR';
  readonly spokenLanguages: string[] = ['pt-BR', 'en-US'];

  readonly techStack: TechStack[] = ['Front-End'];

  readonly skills: SkillSet = {
    languages: ['TypeScript', 'JavaScript', 'HTML5', 'CSS3', 'SCSS'],
    frameworks: ['Angular'],
    libraries: ['Angular Material', 'RxJS'],
    tools: ['Git', 'Angular CLI', 'SonarQube'],
  };

  readonly currentState: CurrentState = {
    focus: 'Reactive, readable web applications built with Angular',
    learning: ['NgRx', 'Vitest', 'Advanced Angular design patterns'],
    inProgress: {
      title: 'Gacha List Generator',
      description:
        'Reactive, drag-and-drop tier list generator for gacha players',
      technologies: ['Angular 22', 'Angular CDK', 'PrimeNG', 'Resource API'],
    },
  };

  greet(): void {
    const nickname = this.firstName.slice(0, 5);
    console.log(
      `Hi! This is ${nickname}. Thanks for your interest in my work.`,
    );
  }
```

```
const jessi = new SoftwareEngineer()
jessi.greet()
