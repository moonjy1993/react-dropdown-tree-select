# Snapshot report for `src\index.test.js`

The actual snapshot is saved in `index.test.js.snap`.

Generated by [AVA](https://ava.li).

## doesn't toggle dropdown if it's disabled

> Snapshot 1

    <div
      className="react-dropdown-tree-select"
      id="rdts"
    >
      <div
        className="dropdown"
      >
        <a
          className="dropdown-trigger arrow disabled bottom"
          onClick={false}
        >
          <Input
            disabled={true}
            inputRef={Function inputRef {}}
            onBlur={Function {}}
            onFocus={Function {}}
            onInputChange={Function {}}
            onTagRemove={Function {}}
            tags={[]}
          />
        </a>
      </div>
    </div>

## renders default radio select state

> Snapshot 1

    <DropdownTreeSelect
      data={
        [
          {
            children: [
              {
                children: [
                  {
                    label: 'item1-1-1',
                    value: 'value1-1-1',
                  },
                  {
                    label: 'item1-1-2',
                    value: 'value1-1-2',
                  },
                ],
                label: 'item1-1',
                value: 'value1-1',
              },
              {
                label: 'item1-2',
                value: 'value1-2',
              },
            ],
            label: 'item1',
            value: 'value1',
          },
          {
            children: [
              {
                children: [
                  {
                    label: 'item2-1-1',
                    value: 'value2-1-1',
                  },
                  {
                    label: 'item2-1-2',
                    value: 'value2-1-2',
                  },
                  {
                    children: [
                      {
                        label: 'item2-1-3-1',
                        value: 'value2-1-3-1',
                      },
                    ],
                    label: 'item2-1-3',
                    value: 'value2-1-3',
                  },
                ],
                label: 'item2-1',
                value: 'value2-1',
              },
              {
                label: 'item2-2',
                value: 'value2-2',
              },
            ],
            label: 'item2',
            value: 'value2',
          },
        ]
      }
      id="rdts"
      onBlur={Function onBlur {}}
      onChange={Function onChange {}}
      onFocus={Function onFocus {}}
      radioSelect={true}
    >
      <div
        className="react-dropdown-tree-select"
        id="rdts"
      >
        <div
          className="dropdown radio-select"
        >
          <a
            className="dropdown-trigger arrow bottom"
            onClick={Function {}}
          >
            <Input
              inputRef={Function inputRef {}}
              onBlur={Function {}}
              onFocus={Function {}}
              onInputChange={Function {}}
              onTagRemove={Function {}}
              tags={[]}
            >
              <ul
                className="tag-list"
              >
                <li
                  className="tag-item"
                >
                  <input
                    className="search"
                    onBlur={Function {}}
                    onChange={Function {}}
                    onFocus={Function {}}
                    placeholder="Choose..."
                    type="text"
                  />
                </li>
              </ul>
            </Input>
          </a>
        </div>
      </div>
    </DropdownTreeSelect>

## renders default state

> Snapshot 1

    <DropdownTreeSelect
      data={
        [
          {
            children: [
              {
                children: [
                  {
                    label: 'item1-1-1',
                    value: 'value1-1-1',
                  },
                  {
                    label: 'item1-1-2',
                    value: 'value1-1-2',
                  },
                ],
                label: 'item1-1',
                value: 'value1-1',
              },
              {
                label: 'item1-2',
                value: 'value1-2',
              },
            ],
            label: 'item1',
            value: 'value1',
          },
          {
            children: [
              {
                children: [
                  {
                    label: 'item2-1-1',
                    value: 'value2-1-1',
                  },
                  {
                    label: 'item2-1-2',
                    value: 'value2-1-2',
                  },
                  {
                    children: [
                      {
                        label: 'item2-1-3-1',
                        value: 'value2-1-3-1',
                      },
                    ],
                    label: 'item2-1-3',
                    value: 'value2-1-3',
                  },
                ],
                label: 'item2-1',
                value: 'value2-1',
              },
              {
                label: 'item2-2',
                value: 'value2-2',
              },
            ],
            label: 'item2',
            value: 'value2',
          },
        ]
      }
      id="rdts"
      onBlur={Function onBlur {}}
      onChange={Function onChange {}}
      onFocus={Function onFocus {}}
    >
      <div
        className="react-dropdown-tree-select"
        id="rdts"
      >
        <div
          className="dropdown"
        >
          <a
            className="dropdown-trigger arrow bottom"
            onClick={Function {}}
          >
            <Input
              inputRef={Function inputRef {}}
              onBlur={Function {}}
              onFocus={Function {}}
              onInputChange={Function {}}
              onTagRemove={Function {}}
              tags={[]}
            >
              <ul
                className="tag-list"
              >
                <li
                  className="tag-item"
                >
                  <input
                    className="search"
                    onBlur={Function {}}
                    onChange={Function {}}
                    onFocus={Function {}}
                    placeholder="Choose..."
                    type="text"
                  />
                </li>
              </ul>
            </Input>
          </a>
        </div>
      </div>
    </DropdownTreeSelect>

## shows dropdown

> Snapshot 1

    <div
      className="react-dropdown-tree-select"
      id="rdts"
    >
      <div
        className="dropdown"
      >
        <a
          className="dropdown-trigger arrow top"
          onClick={Function {}}
        >
          <Input
            inputRef={Function inputRef {}}
            onBlur={Function {}}
            onFocus={Function {}}
            onInputChange={Function {}}
            onTagRemove={Function {}}
            tags={[]}
          />
        </a>
        <div
          className="dropdown-content"
        >
          <Tree
            clientId="rdts"
            data={
              Map {
                'rdts-0' => {
                  _children: [
                    'rdts-0-0',
                    'rdts-0-1',
                  ],
                  _depth: 0,
                  _id: 'rdts-0',
                  children: undefined,
                  label: 'item1',
                  value: 'value1',
                },
                'rdts-0-0' => {
                  _children: [
                    'rdts-0-0-0',
                    'rdts-0-0-1',
                  ],
                  _depth: 1,
                  _id: 'rdts-0-0',
                  _parent: 'rdts-0',
                  children: undefined,
                  label: 'item1-1',
                  value: 'value1-1',
                },
                'rdts-0-0-0' => {
                  _depth: 2,
                  _id: 'rdts-0-0-0',
                  _parent: 'rdts-0-0',
                  label: 'item1-1-1',
                  value: 'value1-1-1',
                },
                'rdts-0-0-1' => {
                  _depth: 2,
                  _id: 'rdts-0-0-1',
                  _parent: 'rdts-0-0',
                  label: 'item1-1-2',
                  value: 'value1-1-2',
                },
                'rdts-0-1' => {
                  _depth: 1,
                  _id: 'rdts-0-1',
                  _parent: 'rdts-0',
                  label: 'item1-2',
                  value: 'value1-2',
                },
                'rdts-1' => {
                  _children: [
                    'rdts-1-0',
                    'rdts-1-1',
                  ],
                  _depth: 0,
                  _id: 'rdts-1',
                  children: undefined,
                  label: 'item2',
                  value: 'value2',
                },
                'rdts-1-0' => {
                  _children: [
                    'rdts-1-0-0',
                    'rdts-1-0-1',
                    'rdts-1-0-2',
                  ],
                  _depth: 1,
                  _id: 'rdts-1-0',
                  _parent: 'rdts-1',
                  children: undefined,
                  label: 'item2-1',
                  value: 'value2-1',
                },
                'rdts-1-0-0' => {
                  _depth: 2,
                  _id: 'rdts-1-0-0',
                  _parent: 'rdts-1-0',
                  label: 'item2-1-1',
                  value: 'value2-1-1',
                },
                'rdts-1-0-1' => {
                  _depth: 2,
                  _id: 'rdts-1-0-1',
                  _parent: 'rdts-1-0',
                  label: 'item2-1-2',
                  value: 'value2-1-2',
                },
                'rdts-1-0-2' => {
                  _children: [
                    'rdts-1-0-2-0',
                  ],
                  _depth: 2,
                  _id: 'rdts-1-0-2',
                  _parent: 'rdts-1-0',
                  children: undefined,
                  label: 'item2-1-3',
                  value: 'value2-1-3',
                },
                'rdts-1-0-2-0' => {
                  _depth: 3,
                  _id: 'rdts-1-0-2-0',
                  _parent: 'rdts-1-0-2',
                  label: 'item2-1-3-1',
                  value: 'value2-1-3-1',
                },
                'rdts-1-1' => {
                  _depth: 1,
                  _id: 'rdts-1-1',
                  _parent: 'rdts-1',
                  label: 'item2-2',
                  value: 'value2-2',
                },
              }
            }
            onAction={Function {}}
            onCheckboxChange={Function {}}
            onNodeToggle={Function {}}
            pageSize={100}
            searchModeOn={false}
          />
        </div>
      </div>
    </div

## always shows dropdown

> Snapshot 1

    <div
      className="react-dropdown-tree-select"
      id="rdts"
    >
      <div
        className="dropdown"
      >
        <a
          className="dropdown-trigger arrow top"
          onClick={Function {}}
        >
          <Input
            inputRef={Function inputRef {}}
            onBlur={Function {}}
            onFocus={Function {}}
            onInputChange={Function {}}
            onTagRemove={Function {}}
            tags={[]}
          />
        </a>
        <div
          className="dropdown-content"
        >
          <Tree
            clientId="rdts"
            data={
              Map {
                'rdts-0' => {
                  _children: [
                    'rdts-0-0',
                    'rdts-0-1',
                  ],
                  _depth: 0,
                  _id: 'rdts-0',
                  children: undefined,
                  label: 'item1',
                  value: 'value1',
                },
                'rdts-0-0' => {
                  _children: [
                    'rdts-0-0-0',
                    'rdts-0-0-1',
                  ],
                  _depth: 1,
                  _id: 'rdts-0-0',
                  _parent: 'rdts-0',
                  children: undefined,
                  label: 'item1-1',
                  value: 'value1-1',
                },
                'rdts-0-0-0' => {
                  _depth: 2,
                  _id: 'rdts-0-0-0',
                  _parent: 'rdts-0-0',
                  label: 'item1-1-1',
                  value: 'value1-1-1',
                },
                'rdts-0-0-1' => {
                  _depth: 2,
                  _id: 'rdts-0-0-1',
                  _parent: 'rdts-0-0',
                  label: 'item1-1-2',
                  value: 'value1-1-2',
                },
                'rdts-0-1' => {
                  _depth: 1,
                  _id: 'rdts-0-1',
                  _parent: 'rdts-0',
                  label: 'item1-2',
                  value: 'value1-2',
                },
                'rdts-1' => {
                  _children: [
                    'rdts-1-0',
                    'rdts-1-1',
                  ],
                  _depth: 0,
                  _id: 'rdts-1',
                  children: undefined,
                  label: 'item2',
                  value: 'value2',
                },
                'rdts-1-0' => {
                  _children: [
                    'rdts-1-0-0',
                    'rdts-1-0-1',
                    'rdts-1-0-2',
                  ],
                  _depth: 1,
                  _id: 'rdts-1-0',
                  _parent: 'rdts-1',
                  children: undefined,
                  label: 'item2-1',
                  value: 'value2-1',
                },
                'rdts-1-0-0' => {
                  _depth: 2,
                  _id: 'rdts-1-0-0',
                  _parent: 'rdts-1-0',
                  label: 'item2-1-1',
                  value: 'value2-1-1',
                },
                'rdts-1-0-1' => {
                  _depth: 2,
                  _id: 'rdts-1-0-1',
                  _parent: 'rdts-1-0',
                  label: 'item2-1-2',
                  value: 'value2-1-2',
                },
                'rdts-1-0-2' => {
                  _children: [
                    'rdts-1-0-2-0',
                  ],
                  _depth: 2,
                  _id: 'rdts-1-0-2',
                  _parent: 'rdts-1-0',
                  children: undefined,
                  label: 'item2-1-3',
                  value: 'value2-1-3',
                },
                'rdts-1-0-2-0' => {
                  _depth: 3,
                  _id: 'rdts-1-0-2-0',
                  _parent: 'rdts-1-0-2',
                  label: 'item2-1-3-1',
                  value: 'value2-1-3-1',
                },
                'rdts-1-1' => {
                  _depth: 1,
                  _id: 'rdts-1-1',
                  _parent: 'rdts-1',
                  label: 'item2-2',
                  value: 'value2-2',
                },
              }
            }
            onAction={Function {}}
            onCheckboxChange={Function {}}
            onNodeToggle={Function {}}
            pageSize={100}
            searchModeOn={false}
          />
        </div>
      </div>
    </div>
