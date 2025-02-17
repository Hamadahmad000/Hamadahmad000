### Hello world 👋  I'm Hamad
![Description](https://i.gifer.com/3AyY.gif)


```typescript
const websiteUrl = '';

const me: PersonalInfo = {
  title: 'Senior React Native Developer',
  contactInfo: {
    email: new URL('mailto:hamadahmad000143@gmail.com'),
    linkedIn: new URL('https://www.linkedin.com/in/hamad-ahmad-40470825b?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=ios_app'),
    github: new URL('https://github.com/hamadahmad000'),
    facebook: new URL('https://www.facebook.com/hamad.mughal.108?mibextid=LQQJ4d'),
    portfolio: new URL(''),
    facefolio: new URL(''),
    website: new URL(`https://${websiteUrl}`),
    resume: new URL(`https://${websiteUrl}/downloads/viewHamadAhmadResume.pdf`),
  },
  reactNativeInfo: {
    experienceYears: '5+',
    projectsCount: 'Many!',
    apps: [
      {
        hasPublishedApps: true,
        appsCount: 4, // iOS apps
      },
      {
        hasPublishedApps: true,
        appsCount: 6, // Android apps
      },
    ],
    architecturesAndTools: [
      'React Native Web',
      'Redux',
      'Clean Architecture',
      'Firebase',
      'MongoDB',
      'Node.js',
    ],
  },
  otherSkills: [
    'UI / UX',
    'MongoDB',
    'JavaScript',
    'NodeJS',
    'HTML / CSS',
    'TypeScript',
    'Express',
  ],
  projects: [
    {
      name: 'DateChatAI',
      role: 'Senior React Native Developer',
      platforms: { ios: true, android: true },
      url: new URL('https://datechatai.com'),
    },
    {
      name: 'My FaceFolio',
      role: 'Senior React Native Developer',
      platforms: { web: true },
      url: new URL('https://facefolio.dctech.dev'),
    },
    {
      name: 'Baseball Cuba',
      role: 'Senior React Native Developer',
      platforms: { ios: true, android: true },
    },
    {
      name: 'My React Native Web Portfolio',
      role: 'Senior React Native Developer',
      platforms: { web: true },
      url: new URL('https://portfolio.dctech.dev'),
    },
    {
      name: 'ProAnimals',
      role: 'Senior React Native Developer',
      platforms: { ios: true, android: true },
    },
    {
      name: 'Cashews Finance',
      role: 'Senior React Native Developer',
      platforms: { ios: true, android: true },
      url: new URL(`https://${websiteUrl}/cashews-finance`),
    },
    {
      name: 'Self-Service kiosk for Citroën',
      role: 'Full Stack Software Engineer',
      platforms: { android: true },
      url: new URL(`https://${websiteUrl}/citroen`),
    },
    {
      name: 'PedidoFacil',
      role: 'Full Stack Software Engineer',
      platforms: { ios: true, android: true },
      url: new URL(`https://${websiteUrl}/pedidofacil`),
    },
    {
      name: 'EnvioFacil',
      role: 'Full Stack Software Engineer',
      platforms: { ios: true, android: true },
      url: new URL(`https://${websiteUrl}/enviofacil`),
    },
  ],
  setStatus: function (status: Status): void {
    console.log(`Learning Cool Stuff: ${status.learningCoolStuff}, Open to New Projects: ${status.openToNewProjects}`);
  },
};

// Set status
me.setStatus({
  learningCoolStuff: true,
  openToNewProjects: true,
});

