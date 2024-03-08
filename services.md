# Accessibility

## WCAG Level
### A
- Audit
	- Web
		- Windows
			- Color Contrast Check
				- (Part of tools check)
			- Test Resize Check
			- UX Check
		- Mac
			- Color Contrast Check
				- (Part of tools check)
			- Test Resize Check
			- 
	- Mobile
		- iOS
			- Color Contrast Check
				- (Part of tools check)
			- Test Resize Check
			- UX Check
		- Android
			- Color Contrast Check
				- (Part of tools check)
			- Test Resize Check
			- UX Check

## WCAG Level

### AA
- Audit
	- Web
		- Windows
			- NVDA check
				- Follow User Guide
				- Record session
			- Color Contrast Check
				- (Part of tools check)
			- Test Resize Check
		- Mac
			- VoiceOver check
				- Follow User Guide
				- Record session
			- Color Contrast Check
				- (Part of tools check)
			- Test Resize Check
	- Mobile
		- iOS
			- VoiceOver check
				- Follow User Guide
				- Record session
			- Code Check (SonarQube)
				- Access to codebase
					- Yes
					- No
			- Color Contrast Check
				- (Part of tools check)
			- Test Resize Check
		- Android
			- TalkBack check
				- Follow User Guide
				- Record session
			- Code Check (SonarQube)
				- Access to codebase
					- Yes
					- No
			- Color Contrast Check
				- (Part of tools check)
			- Test Resize Check

## Tools

### Self-hosted
- Browser based automation to return screenreader output
	- Test Framework
		- Cypress
			- Add a11y/axe package
		- Cucumber
			- Add a11y/axe package
		- Jest
			- Add a11y/axe package
- Web-based dashboard
	- Login barrier
		- Yes
			- Login barrier
				- Add login script
			- Add urls to dashboard
		-   - Add urls to dashboard
- SonarQube code check
- Pa11y/Axe scanning tool
	- Login barrier
		- Yes
			- Login barrier
				- Add login script
			- Sitemap?
				- Yes
					- Add url
				- No
					- Add urls to list
		-   - Sitemap?
			  	- Yes  
			  		- Add url  
			  	- No  
			  		- Add urls to list  
			
- Lighthouse check

## Strategy

### Things to check regards Design
- Check color contrast
- Check behaviour on resize
- Check forms in detail

### Things to check regards Development
- Build server
	- Azure
		- Add plugins
			- SonarQubbe
			- Pa11y Ci/Axe Scan
	- Jenkins
		- Add plugins
			- SonarQubbe
			- Pa11y Ci/Axe Scan
	- Gitlab
		- Add plugins
			- SonarQubbe
			- Pa11y Ci/Axe Scan
- Build cycle
	- Run CLI tool with each build
- Test adhoc with browser add-ons
	- HTML Sniffer
	- Tota11y
- Test adhoc with mobile apps
	- ANDROID:App Accessibility Scanner Checker
	- ANDROID: AXE App Accessibility Checker

### Disabilities to consider regards UX
- Autistic spectrum
- Dyslexia
- Age
- Language
- Culture
- Education
- Economic position
- Technological aptitude
- Cognitive
- Physical Mobility
- Auditory
