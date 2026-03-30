# Components System

## Purpose
Defines reusable UI components such as buttons, cards, navigation, and forms.

Components must be reusable, consistent, and independent of specific pages.

---

## 1. Buttons

### button-primary
- display: inline-flex
- align-items: center
- justify-content: center
- padding-top:20px
- padding-bottom:20px
- padding-left:30px
- padding-right:30px
- font-size: 18px
- font-weight: bold
- background-color:  primary-3
- color: white
- border-radius: 54px
- transition:

### button-secondary
- display: inline-flex
- align-items: center
- justify-content: center
- padding-top:15px
- padding-bottom:15px
- padding-left:24px
- padding-right:24px
- font-size: 16px
- font-weight: bold
- background-color:  primary-3
- color: white
- border-radius: 62px
- transition:

---

## 2. Cards

### card-basic
- padding-top: 18px
- padding-bottom: 18px
- padding-left: 18px
- padding-right: 18px
- background-color: white
- border-radius: 12px
- box-shadow:

### card-content
- display: flex
- flex-direction: column
- gap: 10px

### card-secondary
- background-color: gray
- border-radius: 12px
- height: 100%
- width: 100%
- box-shadow:
---

## 3. Navigation

### navbar-wrapper
- display: flex
- justify-content: space-between
- align-items: center
- height:
- padding-bottom: 24px
- padding-top:24px
- padding-left:0px
- padding-right:0px

### nav-menu
- display: flex
- gap: 32px

---

## 4. Forms

### form-input
- width: 100%
- padding:
- border:
- border-radius:

### form-button
- use: button-primary

---

## 5. Component Structure Example

<div class="card-basic">
  <div class="card-content">
    <h3 class="heading-h3">Title</h3>
    <p class="text-size-medium">Text</p>
    <a class="button-primary">Action</a>
  </div>
</div>

---

## 6. States (IMPORTANT)

### button-primary:hover
- background-color:

### button-primary:active
- transform:

---

## 7. Rules

- Components must be reusable
- No page-specific styling inside components
- Use spacing + typography systems
- Avoid hardcoded values

---

## 8. Connections

[[button-primary]]
[[card-basic]]
[[nav-bar]]
[[form-input]]