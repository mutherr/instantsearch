---
title: CurrentRefinedValues
type: widget
html: |
  <div class="ais-CurrentRefinedValues">
    <div class="ais-CurrentRefinedValues-header ais-header">
      Header (optional)
    </div>
    <div class="ais-CurrentRefinedValues-body ais-body">
      <ul class="ais-CurrentRefinedValues-list">
        <li class="ais-CurrentRefinedValues-item">
          <button class="ais-CurrentRefinedValues-button">
            Movies & TV Shows <span class="ais-CurrentRefinedValues-count">1,574</span>
          </button>
        </li>
        <li class="ais-CurrentRefinedValues-item">
          <button class="ais-CurrentRefinedValues-button">
            Others <span class="ais-CurrentRefinedValues-count">2,450</span>
          </button>
        </li>
      </ul>
      <button class="ais-CurrentRefinedValues-clearAll">
        Clear all
      </button>
    </div>
    <div class="ais-CurrentRefinedValues-footer ais-footer">
      Footer (optional)
    </div>
  </div>
classes:
  - name: .ais-CurrentRefinedValues
    description: the root div of the widget
  - name: .ais-CurrentRefinedValues-header
    description: the header of the widget
  - name: .ais-CurrentRefinedValues-body
    description: the body of the widget
  - name: .ais-CurrentRefinedValues-list
    description: the list of all refined items
  - name: .ais-CurrentRefinedValues-item
    description: the refined list item
  - name: .ais-CurrentRefinedValues-button
    description: the clickable refined element
  - name: .ais-CurrentRefinedValues-count
    description: the count of refined values for each item
  - name: .ais-CurrentRefinedValues-clearAll
    description: the reset button for current selected values
  - name: .ais-CurrentRefinedValues-footer
    description: the footer of the widget
---