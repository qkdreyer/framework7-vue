<template>
  <f7-page>
    <f7-navbar title="Data Table" back-link="Back"></f7-navbar>
    <f7-block-title>Plain table</f7-block-title>
    <div class="data-table">
      <table>
        <thead>
          <tr>
            <th class="label-cell">Desert (100g serving)</th>
            <th class="numeric-cell">Calories</th>
            <th class="numeric-cell">Fat (g)</th>
            <th class="numeric-cell">Carbs</th>
            <th class="numeric-cell">Protein (g)</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td class="label-cell">Frozen yogurt</td>
            <td class="numeric-cell">159</td>
            <td class="numeric-cell">6.0</td>
            <td class="numeric-cell">24</td>
            <td class="numeric-cell">4.0</td>
          </tr>
          <tr>
            <td class="label-cell">Ice cream sandwich</td>
            <td class="numeric-cell">237</td>
            <td class="numeric-cell">9.0</td>
            <td class="numeric-cell">37</td>
            <td class="numeric-cell">4.4</td>
          </tr>
          <tr>
            <td class="label-cell">Eclair</td>
            <td class="numeric-cell">262</td>
            <td class="numeric-cell">16.0</td>
            <td class="numeric-cell">24</td>
            <td class="numeric-cell">6.0</td>
          </tr>
          <tr>
            <td class="label-cell">Cupcake</td>
            <td class="numeric-cell">305</td>
            <td class="numeric-cell">3.7</td>
            <td class="numeric-cell">67</td>
            <td class="numeric-cell">4.3</td>
          </tr>
        </tbody>
      </table>
    </div>
    <f7-block-title>Within card</f7-block-title>
    <div class="card data-table">
      <table>
        <thead>
          <tr>
            <th class="label-cell">Desert (100g serving)</th>
            <th class="numeric-cell">Calories</th>
            <th class="numeric-cell">Fat (g)</th>
            <th class="numeric-cell">Carbs</th>
            <th class="numeric-cell">Protein (g)</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td class="label-cell">Frozen yogurt</td>
            <td class="numeric-cell">159</td>
            <td class="numeric-cell">6.0</td>
            <td class="numeric-cell">24</td>
            <td class="numeric-cell">4.0</td>
          </tr>
          <tr>
            <td class="label-cell">Ice cream sandwich</td>
            <td class="numeric-cell">237</td>
            <td class="numeric-cell">9.0</td>
            <td class="numeric-cell">37</td>
            <td class="numeric-cell">4.4</td>
          </tr>
          <tr>
            <td class="label-cell">Eclair</td>
            <td class="numeric-cell">262</td>
            <td class="numeric-cell">16.0</td>
            <td class="numeric-cell">24</td>
            <td class="numeric-cell">6.0</td>
          </tr>
          <tr>
            <td class="label-cell">Cupcake</td>
            <td class="numeric-cell">305</td>
            <td class="numeric-cell">3.7</td>
            <td class="numeric-cell">67</td>
            <td class="numeric-cell">4.3</td>
          </tr>
        </tbody>
      </table>
    </div>
    <f7-block-title>Selectable rows</f7-block-title>
    <div class="data-table data-table-init card">
      <table>
        <thead>
          <tr>
            <th class="checkbox-cell">
              <label class="checkbox">
                <input type="checkbox"/>
                <i class="icon-checkbox"></i>
              </label>
            </th>
            <th class="label-cell">Desert (100g serving)</th>
            <th class="numeric-cell">Calories</th>
            <th class="numeric-cell">Fat (g)</th>
            <th class="numeric-cell">Carbs</th>
            <th class="numeric-cell">Protein (g)</th>
            <th class="checkbox-cell">
              <label class="checkbox">
                <input type="checkbox"/>
                <i class="icon-checkbox"></i>
              </label>
              <span>In Stock</span>
            </th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td class="checkbox-cell">
              <label class="checkbox">
                <input type="checkbox"/>
                <i class="icon-checkbox"></i>
              </label>
            </td>
            <td class="label-cell">Frozen yogurt</td>
            <td class="numeric-cell">159</td>
            <td class="numeric-cell">6.0</td>
            <td class="numeric-cell">24</td>
            <td class="numeric-cell">4.0</td>
            <td class="checkbox-cell">
              <label class="checkbox">
                <input type="checkbox"/>
                <i class="icon-checkbox"></i>
              </label>
            </td>
          </tr>
          <tr>
            <td class="checkbox-cell">
              <label class="checkbox">
                <input type="checkbox"/>
                <i class="icon-checkbox"></i>
              </label>
            </td>
            <td class="label-cell">Ice cream sandwich</td>
            <td class="numeric-cell">237</td>
            <td class="numeric-cell">9.0</td>
            <td class="numeric-cell">37</td>
            <td class="numeric-cell">4.4</td>
            <td class="checkbox-cell">
              <label class="checkbox">
                <input type="checkbox"/>
                <i class="icon-checkbox"></i>
              </label>
            </td>
          </tr>
          <tr>
            <td class="checkbox-cell">
              <label class="checkbox">
                <input type="checkbox"/>
                <i class="icon-checkbox"></i>
              </label>
            </td>
            <td class="label-cell">Eclair</td>
            <td class="numeric-cell">262</td>
            <td class="numeric-cell">16.0</td>
            <td class="numeric-cell">24</td>
            <td class="numeric-cell">6.0</td>
            <td class="checkbox-cell">
              <label class="checkbox">
                <input type="checkbox"/>
                <i class="icon-checkbox"></i>
              </label>
            </td>
          </tr>
          <tr>
            <td class="checkbox-cell">
              <label class="checkbox">
                <input type="checkbox"/>
                <i class="icon-checkbox"></i>
              </label>
            </td>
            <td class="label-cell">Cupcake</td>
            <td class="numeric-cell">305</td>
            <td class="numeric-cell">3.7</td>
            <td class="numeric-cell">67</td>
            <td class="numeric-cell">4.3</td>
            <td class="checkbox-cell">
              <label class="checkbox">
                <input type="checkbox"/>
                <i class="icon-checkbox"></i>
              </label>
            </td>
          </tr>
        </tbody>
      </table>
    </div>
    <f7-block-title>Tablet-only columns</f7-block-title>
    <div class="block-header">
      <p>"Comments" column will be visible only on large screen devices (tablets)</p>
    </div>
    <div class="data-table data-table-init card">
      <table>
        <thead>
          <tr>
            <th class="checkbox-cell">
              <label class="checkbox">
                <input type="checkbox"/>
                <i class="icon-checkbox"></i>
              </label>
            </th>
            <th class="label-cell">Desert (100g serving)</th>
            <th class="numeric-cell">Calories</th>
            <th class="numeric-cell">Fat (g)</th>
            <th class="numeric-cell">Carbs</th>
            <th class="numeric-cell">Protein (g)</th>
            <th class="tablet-only"><f7-icon if-ios="f7:chat_fill" if-md="material:message"></f7-icon> Comments</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td class="checkbox-cell">
              <label class="checkbox">
                <input type="checkbox"/>
                <i class="icon-checkbox"></i>
              </label>
            </td>
            <td class="label-cell">Frozen yogurt</td>
            <td class="numeric-cell">159</td>
            <td class="numeric-cell">6.0</td>
            <td class="numeric-cell">24</td>
            <td class="numeric-cell">4.0</td>
            <td class="tablet-only">I like frozen yogurt</td>
          </tr>
          <tr>
            <td class="checkbox-cell">
              <label class="checkbox">
                <input type="checkbox"/>
                <i class="icon-checkbox"></i>
              </label>
            </td>
            <td class="label-cell">Ice cream sandwich</td>
            <td class="numeric-cell">237</td>
            <td class="numeric-cell">9.0</td>
            <td class="numeric-cell">37</td>
            <td class="numeric-cell">4.4</td>
            <td class="tablet-only">But like ice cream more</td>
          </tr>
          <tr>
            <td class="checkbox-cell">
              <label class="checkbox">
                <input type="checkbox"/>
                <i class="icon-checkbox"></i>
              </label>
            </td>
            <td class="label-cell">Eclair</td>
            <td class="numeric-cell">262</td>
            <td class="numeric-cell">16.0</td>
            <td class="numeric-cell">24</td>
            <td class="numeric-cell">6.0</td>
            <td class="tablet-only">Super tasty</td>
          </tr>
          <tr>
            <td class="checkbox-cell">
              <label class="checkbox">
                <input type="checkbox"/>
                <i class="icon-checkbox"></i>
              </label>
            </td>
            <td class="label-cell">Cupcake</td>
            <td class="numeric-cell">305</td>
            <td class="numeric-cell">3.7</td>
            <td class="numeric-cell">67</td>
            <td class="numeric-cell">4.3</td>
            <td class="tablet-only">Don't like it</td>
          </tr>
        </tbody>
      </table>
    </div>
    <f7-block-title>Within card with title and actions</f7-block-title>
    <div class="data-table data-table-init card">
      <div class="card-header">
        <div class="data-table-title">Nutrition</div>
        <div class="data-table-actions">
          <f7-link icon-if-ios="f7:sort" icon-if-md="material:sort"></f7-link>
          <f7-link icon-if-ios="f7:more_vertical_round" icon-if-md="material:more_vert"></f7-link>
        </div>
      </div>
      <div class="card-content">
        <table>
          <thead>
            <tr>
              <th class="checkbox-cell">
                <label class="checkbox">
                  <input type="checkbox"/>
                  <i class="icon-checkbox"></i>
                </label>
              </th>
              <th class="label-cell">Desert (100g serving)</th>
              <th class="numeric-cell">Calories</th>
              <th class="numeric-cell">Fat (g)</th>
              <th class="numeric-cell">Carbs</th>
              <th class="numeric-cell">Protein (g)</th>
              <th class="tablet-only"><f7-icon if-ios="f7:chat_fill" if-md="material:message"></f7-icon> Comments</th>
            </tr>
          </thead>
          <tbody>
            <tr>
              <td class="checkbox-cell">
                <label class="checkbox">
                  <input type="checkbox"/>
                  <i class="icon-checkbox"></i>
                </label>
              </td>
              <td class="label-cell">Frozen yogurt</td>
              <td class="numeric-cell">159</td>
              <td class="numeric-cell">6.0</td>
              <td class="numeric-cell">24</td>
              <td class="numeric-cell">4.0</td>
              <td class="tablet-only">I like frozen yogurt</td>
            </tr>
            <tr>
              <td class="checkbox-cell">
                <label class="checkbox">
                  <input type="checkbox"/>
                  <i class="icon-checkbox"></i>
                </label>
              </td>
              <td class="label-cell">Ice cream sandwich</td>
              <td class="numeric-cell">237</td>
              <td class="numeric-cell">9.0</td>
              <td class="numeric-cell">37</td>
              <td class="numeric-cell">4.4</td>
              <td class="tablet-only">But like ice cream more</td>
            </tr>
            <tr>
              <td class="checkbox-cell">
                <label class="checkbox">
                  <input type="checkbox"/>
                  <i class="icon-checkbox"></i>
                </label>
              </td>
              <td class="label-cell">Eclair</td>
              <td class="numeric-cell">262</td>
              <td class="numeric-cell">16.0</td>
              <td class="numeric-cell">24</td>
              <td class="numeric-cell">6.0</td>
              <td class="tablet-only">Super tasty</td>
            </tr>
            <tr>
              <td class="checkbox-cell">
                <label class="checkbox">
                  <input type="checkbox"/>
                  <i class="icon-checkbox"></i>
                </label>
              </td>
              <td class="label-cell">Cupcake</td>
              <td class="numeric-cell">305</td>
              <td class="numeric-cell">3.7</td>
              <td class="numeric-cell">67</td>
              <td class="numeric-cell">4.3</td>
              <td class="tablet-only">Don't like it</td>
            </tr>
          </tbody>
        </table>
      </div>
    </div>
    <f7-block-title>Sortable columns</f7-block-title>
    <div class="data-table data-table-init card">
      <div class="card-header">
        <div class="data-table-title">Nutrition</div>
        <div class="data-table-actions">
          <f7-link icon-if-ios="f7:sort" icon-if-md="material:sort"></f7-link>
          <f7-link icon-if-ios="f7:more_vertical_round" icon-if-md="material:more_vert"></f7-link>
        </div>
      </div>
      <div class="card-content">
        <table>
          <thead>
            <tr>
              <th class="checkbox-cell">
                <label class="checkbox">
                  <input type="checkbox"/>
                  <i class="icon-checkbox"></i>
                </label>
              </th>
              <th class="label-cell sortable-cell sortable-cell-active">Desert (100g serving)</th>
              <th class="numeric-cell sortable-cell">Calories</th>
              <th class="numeric-cell sortable-cell">Fat (g)</th>
              <th class="numeric-cell sortable-cell">Carbs</th>
              <th class="numeric-cell sortable-cell">Protein (g)</th>
              <th class="tablet-only"><f7-icon if-ios="f7:chat_fill" if-md="material:message"></f7-icon> Comments</th>
            </tr>
          </thead>
          <tbody>
            <tr>
              <td class="checkbox-cell">
                <label class="checkbox">
                  <input type="checkbox"/>
                  <i class="icon-checkbox"></i>
                </label>
              </td>
              <td class="label-cell">Frozen yogurt</td>
              <td class="numeric-cell">159</td>
              <td class="numeric-cell">6.0</td>
              <td class="numeric-cell">24</td>
              <td class="numeric-cell">4.0</td>
              <td class="tablet-only">I like frozen yogurt</td>
            </tr>
            <tr>
              <td class="checkbox-cell">
                <label class="checkbox">
                  <input type="checkbox"/>
                  <i class="icon-checkbox"></i>
                </label>
              </td>
              <td class="label-cell">Ice cream sandwich</td>
              <td class="numeric-cell">237</td>
              <td class="numeric-cell">9.0</td>
              <td class="numeric-cell">37</td>
              <td class="numeric-cell">4.4</td>
              <td class="tablet-only">But like ice cream more</td>
            </tr>
            <tr>
              <td class="checkbox-cell">
                <label class="checkbox">
                  <input type="checkbox"/>
                  <i class="icon-checkbox"></i>
                </label>
              </td>
              <td class="label-cell">Eclair</td>
              <td class="numeric-cell">262</td>
              <td class="numeric-cell">16.0</td>
              <td class="numeric-cell">24</td>
              <td class="numeric-cell">6.0</td>
              <td class="tablet-only">Super tasty</td>
            </tr>
            <tr>
              <td class="checkbox-cell">
                <label class="checkbox">
                  <input type="checkbox"/>
                  <i class="icon-checkbox"></i>
                </label>
              </td>
              <td class="label-cell">Cupcake</td>
              <td class="numeric-cell">305</td>
              <td class="numeric-cell">3.7</td>
              <td class="numeric-cell">67</td>
              <td class="numeric-cell">4.3</td>
              <td class="tablet-only">Don't like it</td>
            </tr>
          </tbody>
        </table>
      </div>
    </div>
    <f7-block-title>With title and different actions on select</f7-block-title>
    <div class="data-table data-table-init card">
      <div class="card-header">
        <div class="data-table-header">
          <div class="data-table-title">Nutrition</div>
          <div class="data-table-actions">
            <f7-link icon-if-ios="f7:sort" icon-if-md="material:sort"></f7-link>
            <f7-link icon-if-ios="f7:more_vertical_round" icon-if-md="material:more_vert"></f7-link>
          </div>
        </div>
        <div class="data-table-header-selected">
          <div class="data-table-title-selected"><span class="data-table-selected-count"></span> items selected</div>
          <div class="data-table-actions">
            <f7-link icon-if-ios="f7:trash" icon-if-md="material:delete"></f7-link>
            <f7-link icon-if-ios="f7:more_vertical_round" icon-if-md="material:more_vert"></f7-link>
          </div>
        </div>
      </div>
      <div class="card-content">
        <table>
          <thead>
            <tr>
              <th class="checkbox-cell">
                <label class="checkbox">
                  <input type="checkbox"/>
                  <i class="icon-checkbox"></i>
                </label>
              </th>
              <th class="label-cell">Desert (100g serving)</th>
              <th class="numeric-cell">Calories</th>
              <th class="numeric-cell">Fat (g)</th>
              <th class="numeric-cell">Carbs</th>
              <th class="numeric-cell">Protein (g)</th>
              <th class="tablet-only"><f7-icon if-ios="f7:chat_fill" if-md="material:message"></f7-icon> Comments</th>
            </tr>
          </thead>
          <tbody>
            <tr>
              <td class="checkbox-cell">
                <label class="checkbox">
                  <input type="checkbox"/>
                  <i class="icon-checkbox"></i>
                </label>
              </td>
              <td class="label-cell">Frozen yogurt</td>
              <td class="numeric-cell">159</td>
              <td class="numeric-cell">6.0</td>
              <td class="numeric-cell">24</td>
              <td class="numeric-cell">4.0</td>
              <td class="tablet-only">I like frozen yogurt</td>
            </tr>
            <tr>
              <td class="checkbox-cell">
                <label class="checkbox">
                  <input type="checkbox"/>
                  <i class="icon-checkbox"></i>
                </label>
              </td>
              <td class="label-cell">Ice cream sandwich</td>
              <td class="numeric-cell">237</td>
              <td class="numeric-cell">9.0</td>
              <td class="numeric-cell">37</td>
              <td class="numeric-cell">4.4</td>
              <td class="tablet-only">But like ice cream more</td>
            </tr>
            <tr>
              <td class="checkbox-cell">
                <label class="checkbox">
                  <input type="checkbox"/>
                  <i class="icon-checkbox"></i>
                </label>
              </td>
              <td class="label-cell">Eclair</td>
              <td class="numeric-cell">262</td>
              <td class="numeric-cell">16.0</td>
              <td class="numeric-cell">24</td>
              <td class="numeric-cell">6.0</td>
              <td class="tablet-only">Super tasty</td>
            </tr>
            <tr>
              <td class="checkbox-cell">
                <label class="checkbox">
                  <input type="checkbox"/>
                  <i class="icon-checkbox"></i>
                </label>
              </td>
              <td class="label-cell">Cupcake</td>
              <td class="numeric-cell">305</td>
              <td class="numeric-cell">3.7</td>
              <td class="numeric-cell">67</td>
              <td class="numeric-cell">4.3</td>
              <td class="tablet-only">Don't like it</td>
            </tr>
          </tbody>
        </table>
      </div>
    </div>
    <f7-block-title>Alternate header with actions</f7-block-title>
    <div class="data-table data-table-init card">
      <div class="card-header">
        <div class="data-table-links"><a class="link">Add</a><a class="link">Remove</a></div>
        <div class="data-table-actions">
          <f7-link icon-if-ios="f7:sort" icon-if-md="material:sort"></f7-link>
          <f7-link icon-if-ios="f7:more_vertical_round" icon-if-md="material:more_vert"></f7-link>
        </div>
      </div>
      <div class="card-content">
        <table>
          <thead>
            <tr>
              <th class="checkbox-cell">
                <label class="checkbox">
                  <input type="checkbox"/>
                  <i class="icon-checkbox"></i>
                </label>
              </th>
              <th class="label-cell">Desert (100g serving)</th>
              <th class="numeric-cell">Calories</th>
              <th class="numeric-cell">Fat (g)</th>
              <th class="numeric-cell">Carbs</th>
              <th class="numeric-cell">Protein (g)</th>
              <th class="tablet-only"><f7-icon if-ios="f7:chat_fill" if-md="material:message"></f7-icon> Comments</th>
              <th></th>
            </tr>
          </thead>
          <tbody>
            <tr>
              <td class="checkbox-cell">
                <label class="checkbox">
                  <input type="checkbox"/>
                  <i class="icon-checkbox"></i>
                </label>
              </td>
              <td class="label-cell">Frozen yogurt</td>
              <td class="numeric-cell">159</td>
              <td class="numeric-cell">6.0</td>
              <td class="numeric-cell">24</td>
              <td class="numeric-cell">4.0</td>
              <td class="tablet-only">I like frozen yogurt</td>
              <td class="actions-cell">
                <f7-link icon-if-ios="f7:compose" icon-if-md="material:edit"></f7-link>
                <f7-link icon-if-ios="f7:trash" icon-if-md="material:delete"></f7-link>
              </td>
            </tr>
            <tr>
              <td class="checkbox-cell">
                <label class="checkbox">
                  <input type="checkbox"/>
                  <i class="icon-checkbox"></i>
                </label>
              </td>
              <td class="label-cell">Ice cream sandwich</td>
              <td class="numeric-cell">237</td>
              <td class="numeric-cell">9.0</td>
              <td class="numeric-cell">37</td>
              <td class="numeric-cell">4.4</td>
              <td class="tablet-only">But like ice cream more</td>
              <td class="actions-cell">
                <f7-link icon-if-ios="f7:compose" icon-if-md="material:edit"></f7-link>
                <f7-link icon-if-ios="f7:trash" icon-if-md="material:delete"></f7-link>
              </td>
            </tr>
            <tr>
              <td class="checkbox-cell">
                <label class="checkbox">
                  <input type="checkbox"/>
                  <i class="icon-checkbox"></i>
                </label>
              </td>
              <td class="label-cell">Eclair</td>
              <td class="numeric-cell">262</td>
              <td class="numeric-cell">16.0</td>
              <td class="numeric-cell">24</td>
              <td class="numeric-cell">6.0</td>
              <td class="tablet-only">Super tasty</td>
              <td class="actions-cell">
                <f7-link icon-if-ios="f7:compose" icon-if-md="material:edit"></f7-link>
                <f7-link icon-if-ios="f7:trash" icon-if-md="material:delete"></f7-link>
              </td>
            </tr>
            <tr>
              <td class="checkbox-cell">
                <label class="checkbox">
                  <input type="checkbox"/>
                  <i class="icon-checkbox"></i>
                </label>
              </td>
              <td class="label-cell">Cupcake</td>
              <td class="numeric-cell">305</td>
              <td class="numeric-cell">3.7</td>
              <td class="numeric-cell">67</td>
              <td class="numeric-cell">4.3</td>
              <td class="tablet-only">Don't like it</td>
              <td class="actions-cell">
                <f7-link icon-if-ios="f7:compose" icon-if-md="material:edit"></f7-link>
                <f7-link icon-if-ios="f7:trash" icon-if-md="material:delete"></f7-link>
              </td>
            </tr>
          </tbody>
        </table>
      </div>
    </div>
    <f7-block-title>Collapsible</f7-block-title>
    <div class="block-header">
      <p>The following table will be collapsed to kind of List View on small screens:</p>
    </div>
    <div class="card data-table data-table-collapsible data-table-init">
      <div class="card-header">
        <div class="data-table-title">Nutrition</div>
        <div class="data-table-actions">
          <f7-link icon-if-ios="f7:sort" icon-if-md="material:sort"></f7-link>
          <f7-link icon-if-ios="f7:more_vertical_round" icon-if-md="material:more_vert"></f7-link>
        </div>
      </div>
      <div class="card-content">
        <table>
          <thead>
            <tr>
              <th class="label-cell">Desert (100g serving)</th>
              <th class="numeric-cell">Calories</th>
              <th class="numeric-cell">Fat (g)</th>
              <th class="numeric-cell">Carbs</th>
              <th class="numeric-cell">Protein (g)</th>
            </tr>
          </thead>
          <tbody>
            <tr>
              <td class="label-cell">Frozen yogurt</td>
              <td class="numeric-cell">159</td>
              <td class="numeric-cell">6.0</td>
              <td class="numeric-cell">24</td>
              <td class="numeric-cell">4.0</td>
            </tr>
            <tr>
              <td class="label-cell">Ice cream sandwich</td>
              <td class="numeric-cell">237</td>
              <td class="numeric-cell">9.0</td>
              <td class="numeric-cell">37</td>
              <td class="numeric-cell">4.4</td>
            </tr>
            <tr>
              <td class="label-cell">Eclair</td>
              <td class="numeric-cell">262</td>
              <td class="numeric-cell">16.0</td>
              <td class="numeric-cell">24</td>
              <td class="numeric-cell">6.0</td>
            </tr>
            <tr>
              <td class="label-cell">Cupcake</td>
              <td class="numeric-cell">305</td>
              <td class="numeric-cell">3.7</td>
              <td class="numeric-cell">67</td>
              <td class="numeric-cell">4.3</td>
            </tr>
          </tbody>
        </table>
      </div>
    </div>
  </f7-page>
</template>
<script>
  import { f7Navbar, f7Page, f7BlockTitle, f7Link, f7Icon } from 'framework7-vue';

  export default {
    components: {
      f7Navbar,
      f7Page,
      f7BlockTitle,
      f7Link,
      f7Icon,
    },
  };
</script>
