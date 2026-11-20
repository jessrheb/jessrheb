```typescript
class SoftwareEngineer {
  firstName: string = 'Jessicah';
  role: string = 'Technical Assistant';
  company: string = 'CESAR';
  languages: string[] = ['pt-BR', 'en-US'];
  techStack: TechStack[] = ['Front-End'];

  skills: SkillSet = {
    languages: ['TypeScript', 'JavaScript', 'HTML5', 'CSS3', 'SCSS'],
    frameworks: ['Angular'],
    libraries: ['Angular Material', 'RxJS'],
    tools: ['Git', 'Angular CLI', 'SonarQube'],
  };

  currentStatus: CurrentStatus = {
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

```typescript
const jessi = new SoftwareEngineer()
jessi.greet()
