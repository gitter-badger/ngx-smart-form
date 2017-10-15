# ngx-smart-form

ngx-smart-form is an Angular module for generating forms in your application.

# Features

- generates correct angular form based on provided settings
- ...

# Usage

    <ngx-smart-form [settings]="settings" (onSubmit)="onSubmit($event)"></ngx-smart-form>

Where settings look like:

    settings = {
      inputs: {
        field: {
          label: 'Field',
          type: 'text',
        },
      },
    }

and onSubmit:

    onSubmit(form) {
      this.items.push(form);
    }

# Future features

- custom classes
- custom buttons

# TODOs

- Docs
- Travis
- Ghpages
- Codeclimate
- E2E - protractor

## Thanks to

Thanks to [swimlane/ngx-datatable](https://github.com/swimlane/ngx-datatable/),
I used this repo as a point of start to create an angular2+ module.