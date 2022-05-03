### 👋 Hi, I'm Matheus!

```typescript
class About extends Me {
  public role!: EDevRole;
  public mainStack!: EStack;
  public programmingLanguages!: EProgrammingLanguages[];
  public frontendTools!: EFrontendTools[];
  public backendTools!: EBackendTools[];

  constructor(data: About) {
    super(data);
    
    Object.assing(this, data);
  }
}

const niceToMeetYou = (): About => {
  return new About({
    ...me,
    role: EDevRole.FULLSTACK_DEVELOPER,
    mainStack: EStack.NODEJS_WITH_TYPESCRIPT,
    programmingLanguages: [
      EProgrammingLanguages.TYPESCRIPT,
      EProgrammingLanguages.NET_CORE,
      EProgrammingLanguages.PYTHON,
      EProgrammingLanguages.SQL
    ],
    frontendTools: [
      EFrontendTools.REACT_JS,
      EFrontendTools.REACT_NATIVE,
      EFrontendTools.SASS,
      EFrontendTools.BOOTSTRAP,
      EFrontendTools.STYLED_COMPONENTS
    ],
    backendTools: [
      EBackendTools.TYPEORM,
      EBackendTools.PRISMA,
      EBackendTools.TSOA,
      EBackendTools.SWAGGER_UI,
      EBackendTools.FIREBASE
    ]
  });
}

niceToMeetYou();
```
## ☕ Contact me

<div>  
  <a href="https://wa.me/send?phone=5512988988321">
    <img src="https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" alt="WhatsApp" title="WhatsApp" />
  </a>
  
  <a href="https://www.linkedin.com/in/matheuspdomingos/">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" title="LinkedIn" />
  </a>
</div>
