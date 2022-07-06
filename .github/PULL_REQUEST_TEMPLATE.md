Thanks for proposing a pull request!

To help us review the request, please complete the following:

- [ ] sign [contributor license agreement](https://developers.facebook.com/opensource/cla)
- [ ] I've ensured that all existing tests pass and added tests (when/where necessary)
- [ ] I've updated the documentation (when/where necessary) and [Changelog](CHANGELOG.md) (when/where necessary)
- [ ] I've added the proper label to this pull request (e.g. `bug` for bug fixes)

## Pull Request Details

Describe what you accomplished in this pull request (for example, what happens before the change, and after the change)

## Test Plan

Test Plan: **Add your test plan here**

 const response = await fetch(`http://text-processing.com/api/sentiment/`, {
    method: "POST",
    body: `text=${text}`,
    headers: {
      "Content-Type": "application/x-www-form-urlencoded",
    },
  });
  const json = await response.json();
  return json.label === "pos";
}

   var summaries []CategorySummary
    rows, err := db.Query("SELECT category, COUNT(category), AVG(value) FROM tasks GROUP BY category")
    if err != nil {
        return nil, err
    }
    defer rows.Close()
    for rows.Next() {
        var summary CategorySummary
        err := rows.Scan(&summary.Title, &summary.Tasks, &summary.AvgValue)
        if err != nil {
            return nil, err
        }
        summaries = append(summaries, summary)
    }
    return summaries, nil
}

 expenses = []
    for line in expenses_string.splitlines():
        if line.startswith("#"):
            continue
        date, value, currency = line.split(" ")
        expenses.append((datetime.datetime.strptime(date, "%Y-%m-%d"),
                        float(value),
                        currency))
    return expenses

 def change
    create_table :shipping_addresses do |t|
      t.string :name
      t.string :address
      t.string :city
      t.string :zip
      t.string :state
      t.string :phone
      t.string :email
      t.references :shipping_method, index: true, foreign_key: true
      t.references :customer, index: true, foreign_key: true
      t.timestamps null: false
    end
  end
end



