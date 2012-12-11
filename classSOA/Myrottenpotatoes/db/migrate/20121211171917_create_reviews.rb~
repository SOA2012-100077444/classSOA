class CreateReviews < ActiveRecord::Migration
  def up
    create_table 'reviews' do |t|
      t.integer    'potatoes'
      t.text       'comments'
      t.references 'moviegoers'
      t.references 'movies'
    end
  end

  def down; drop_table 'reviews'; end
end
