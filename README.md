# My Portfolio


# Steps:

1. Install angular:

```bash
npm install --global @angular/cli
```

2. Initialize project

```bash
ng new portfolio
```

3. Create Top Bar
```bash
ng generate component top-bar
```

Add this html to file:

```html
<a [routerLink]="['/']">
  <h1>Portfolio</h1>
</a>
```