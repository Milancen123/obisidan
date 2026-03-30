# Utilities System

## Purpose
Defines small, reusable helper classes used to control layout, alignment, visibility, and behavior.

Utilities should be lightweight and reusable across all components and sections.

---

## 1. Display Utilities

### display-block
- display: block

### display-inline-block
- display: inline-block

### display-flex
- display: flex

### display-none
- display: none

---

## 2. Flex Utilities

### flex-row
- display: flex
- flex-direction: row

### flex-column
- display: flex
- flex-direction: column

### flex-center
- display: flex
- align-items: center
- justify-content: center

### flex-between
- display: flex
- justify-content: space-between
- align-items: center

---

## 3. Alignment Utilities

### text-align-center
- text-align: center

### text-align-left
- text-align: left

### text-align-right
- text-align: right

---

## 4. Width Utilities

### width-100
- width: 100%

### max-width-full
- max-width: 100%

---

## 5. Visibility Utilities

### hide
- display: none

### show
- display: block

### hide-tablet
- display: none (tablet and below)

### hide-mobile
- display: none (mobile)

---

## 6. Overflow

### overflow-hidden
- overflow: hidden

---

## 7. Positioning

### position-relative
- position: relative

### position-absolute
- position: absolute

---

## 8. Z-Index

### z-1
- z-index: 1

### z-10
- z-index: 10

---

## 9. Cursor

### cursor-pointer
- cursor: pointer

---

## 10. Rules

- Utilities should do ONE thing only
- Never mix multiple responsibilities in one utility
- Use utilities to avoid creating unnecessary classes
- Combine utilities with components and layout classes

---

## 11. Connections

[[flex-row]]
[[text-align-center]]
[[container-main]]