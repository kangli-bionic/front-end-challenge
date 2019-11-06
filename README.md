# Q-CTRL Front-end Engineering Challenge

The Q-CTRL Front-end Engineering Challenge is a way for applicants to roles within the Q-CTRL Front-end Engineering team to demonstrate their skills and overall approach to front-end web application development.

## Table of Contents

- [The Rules](#the-rules)
- [The Challenge](#the-challenge)
- [Contributing](#contributing)
- [Credits](#credits)
- [License](#license)

## The Rules

- Read and understand [The Challenge](#the-challenge)
- Create a [React](https://reactjs.org/) app that satisfies the [Requirements](#requirements)
- Spend no more than one hour of actual coding time
- Send the link to the repository containing your app to careers@q-ctrl.com

## The Challenge

### Background

There's a new set of product features being planned for [BLACK OPAL](https://q-ctrl.com/products/black-opal/) whereby a customer will be able to create and manage quantum controls. You can think of these controls as being the individual inputs a customer may employ to manipulate their quantum system using the [Q-CTRL App](https://app.q-ctrl.com/).

The first feature in the sprint is to create a page where a customer can view all the controls they have created.

### Requirements

```
Scenario 1: Controls loading
When I visit the Controls page
Then I should see a loading spinner

Scenario 2: Controls loaded
Given I am on the Controls page
When the controls have finished loading
Then I should see all my controls

Scenario 3: Error loading controls
Given I am on the Controls page
And the controls are loading
When the controls cannot be loaded
Then I should see an error
And I should see a button to try again

Scenario 4: Try loading controls again
Given I am on the Controls page
And there has been an error loading controls
When I click the try again button
Then I should see a loading spinner
And the controls should start to load again
```

### Assets

The below assets have been provided to help complete the challenge.

| Asset         | Description                                                                         |
|---------------|-------------------------------------------------------------------------------------|
| controls.json | Sample response in [JSON:API](https://jsonapi.org/) format provided by the API team |
| design.pdf    | Visual design for the feature provided by the Design team                           |
| logo.svg      | Q-CTRL logo provided by the Brand team                                              |

## Contributing

See [Contributing](https://github.com/qctrl/.github/blob/master/CONTRIBUTING.md).

## Credits

See [Contributors](https://github.com/qctrl/front-end-challenge/graphs/contributors).

## License

See [LICENSE](LICENSE).
